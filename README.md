# Machine-Learning-Swift-Object-Detection
I made a Machine Learning application where we the user clicks the camera button and the image is sent to image view.The machine detects the photo and gives the output in the label stating the type of the image. 


## How it works (Pseudocode)
1. Application loads.
2. Click the camera button to take an image.
3. Camera asks for permission (set permission through info.plist)
4. The Camera captures the UI Image.
5. The UI Image is converted to CI Image and then it runs through the model.
6. After CI Image is processed in the model the Model presents the results in associative array with outputs, in the below format


(
                          "Output_name" => 'name of the output',
                          "Result_as_per_the_model" => 'Result in number'
                              )
                              
**Example** 
 
 
(
                          "Output_name" => 'Electrical switch',
                          "Result_as_per_the_model" => '34.67898'
                              )
(
                          "Output_name" => 'Electrical Point',
                          "Result_as_per_the_model" => '76.90947'
                              )
                              
7. Variable is set to get the top results from the array.
8. print it in the label.


## Screenshots of the Application

### User Interface

<img src="Screenshot/User_interface.PNG" width="200" height="400" />

### Permission for camera
<img src="Screenshot/Permission'.PNG" width="200" height="400" />

### Output after the image running through the model

<img src="Screenshot/Demo1.PNG" width="200" height="400" />
<img src="Screenshot/Demo2.PNG" width="200" height="400" />
<img src="Screenshot/Demo3.PNG" width="200" height="400" />
<img src="Screenshot/Demo4.PNG" width="200" height="400" />
<img src="Screenshot/Demo5.PNG" width="200" height="400" />

