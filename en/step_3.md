## Retrain a model with Teachable Machine

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Teachable Machine allows you to easily retrain an image recognition model by uploading classified images to their site and using their cloud services to create a new model.
</div>
<div>
![animation from teachable machine website showing image, sound, and posture recognition](images/teachable_machine.gif){:width="300px"}
</div>
</div>

--- task ---

In a browser window, navigate to the [Teachable Machine website](https://teachablemachine.withgoogle.com/){:target="_blank"}

--- /task ---

--- task ---

Click on the **Get Started** button.

![teachable machine website with the get started button shown](images/teachable_machine_start.png)

--- /task ---

--- task ---

Choose to create an **Image Project**

![teachable machine website with the three model types shown, image project is on the far left](images/teachable_machine_image.png)

--- /task ---

--- task ---

Select **Standard image model** when prompted.

![teachable machine site with options for standard image model and embedded image model shown](images/teachable_machine_computer_type.png)

--- /task ---

--- task ---

Rename **Class 1** to the name of your image directory, and then upload your images from that directory.

![teachable machine site with images uploaded for the Day class](images/teachable_machine_uploade_images.png)

--- /task ---

--- task ---

Repeat this step for your other image directories.

![teachable machine site with three classes of images loaded](images/teachable_machine_3_classes.png)

--- /task ---

--- task ---

Click on the **Train Model** button, to retrain an existing image recognition model.

![teachable machine site with the training process shown](images/teachable_machine_training.png)

--- /task ---

--- task ---

Click on the **Export Model** button button.

![teachable machine site with the export model button shown](images/teachable_machine_export_model.png)

--- /task ---

--- task ---

Select the **Tensorflow Lite** and **EdgeTPU** options and then **Download my model**.

![teachable machine site with the options shown for downloading a model](images/teachable_machine_export_model_options.png)

--- /task ---