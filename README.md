# Gorilla_Catcher
### Image Identification model and GUI

This project is split into two different notebooks, one which creates the image identification model and one which is a GUI in which you can upload your own images and see if it's a gorilla or a human!

91% accuracy overall, with a 50/50 split between humans and gorillas.


## Demonstration of GUI
![demo](https://user-images.githubusercontent.com/116341361/211934484-ef2d1f50-9952-4b98-9622-5647c63c211f.gif)


## Example of output
![demo](https://user-images.githubusercontent.com/116341361/211934611-310b0d6c-496a-4d9d-a416-a4dbb09ff04e.png)



Unfortunately I will not provide the images I have trained the model on, due to the sheer size (30k+ images).


If you want to run the GUI with the provided model, you just need to run the GorillaCatcher.ipynb, provided you have all the modules installed.

For creating a new model with your own images, add your images in seperate folders in /data/. Add your test data seperated into classes in eval_test. Lastly, add mixed images in the test folder, to make sure no data leakage occurs.
