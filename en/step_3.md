## Retrain a model online, with Teachable Machine

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Teachable Machine allows you to easily retrain an image recognition model by uploading images, that have been sorted into classes, to their site and using their cloud services to create a new model.
</div>
<div>
![Animation from the Teachable Machine website showing image, sound, and posture recognition.](images/teachable_machine.gif){:width="300px"}
</div>
</div>

--- task ---

In a browser window, navigate to the [Teachable Machine website](https://teachablemachine.withgoogle.com/).{:target="_blank"}

--- /task ---

--- task ---

Click on the **Get Started** button.

![Teachable Machine website with the 'Get Started' button shown.](images/teachable_machine_start.png)

--- /task ---

--- task ---

Choose to create an **Image Project**.

![Teachable Machine website with the three model types shown. Image Project is on the far left.](images/teachable_machine_image.png)

--- /task ---

--- task ---

Select **Standard image model** when prompted.

![Teachable Machine website with options for 'Standard image model' and 'Embedded image model' shown.](images/teachable_machine_computer_type.png)

--- /task ---

--- task ---

Rename **Class 1** to the name of your image directory, and then upload your images from that directory.

![Teachable Machine website with images uploaded for the Day class.](images/teachable_machine_uploade_images.png)

--- /task ---

--- task ---

Repeat this step for your other image directories.

![Teachable Machine website with three classes of images loaded.](images/teachable_machine_3_classes.png)

--- /task ---

--- task ---

Click on the **Train Model** button, to retrain an existing image recognition model.

![Teachable Machine website with the training process shown.](images/teachable_machine_training.png)

--- /task ---

--- task ---

Click on the **Export Model** button.

![Teachable Machine website with the 'Export Model' button shown.](images/teachable_machine_export_model.png)

--- /task ---

--- task ---

Select the **Tensorflow Lite** and **EdgeTPU** options, and then **Download my model**.

![Teachable Machine website with the options shown for downloading a model.](images/teachable_machine_export_model_options.png)

--- /task ---

You now have a file that is known as a model. It can be used by the Coral TPU to classify new images and tell you whether they were taken during the **day**, **night**, or **twiglight**.

--- task ---

You can now move on to the [Testing your new model](5) step.

--- /task ---
