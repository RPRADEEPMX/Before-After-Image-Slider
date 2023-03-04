# Before-After-Image-Slider

### Objective

This widget is useful to view the two images in the single image viewer where the both images are viewed by sliding the mouse on the image from left to right or vice versa. This is very useful to compare the before and after variations of the same object.

### Dependencies 

Studio pro version 9.19.0
  
### Configuration

•	Create a Entity with the attribute url of type string and generalize with System.Image.

•	Create a Non-persistent entity with two attributes as BeforeUrl and AfterUrl to pass the Both image url simultaneously into the widget. 

![image](https://user-images.githubusercontent.com/126260956/222886612-1e2bd46e-49d4-4e7e-9916-0bdbadc07ab6.png)
	
•	Create Overview and new edit pages for the entity generalize with System.Image. 

![image](https://user-images.githubusercontent.com/126260956/222886621-9c950349-e464-4a0a-8ace-1d18b4db7a1d.png)

•	Create a Nanoflow as shown in below image.

![image](https://user-images.githubusercontent.com/126260956/222886630-85187e00-b52a-4449-a140-d582a674a765.png)
 
•	Configure the above created nanoflow in the “Onclick Edit action” of the save button.

![image](https://user-images.githubusercontent.com/126260956/222886643-18cf3b8a-61a9-4e3c-bee2-eb3394000a3c.png)


•	Upload the images of Before and After in the New Edit page and save the images to view in the overview page.

![image](https://user-images.githubusercontent.com/126260956/222886650-264a43d0-bdba-4bbe-9b94-79bcb7556dc7.png)


•	Select both Before Image and After Image then click on the “Before/AfterAction” Button to trigger the microflow given below

![image](https://user-images.githubusercontent.com/126260956/222886652-59cddd11-8db6-4abd-aefe-fcb93a378a84.png)



### Result

![image](https://user-images.githubusercontent.com/126260956/222886662-526e2fae-1419-4ab3-baf4-2761126436b5.png)

![image](https://user-images.githubusercontent.com/126260956/222886680-026028e5-e8e0-4d55-a2d5-b65f4a7eacbc.png)



        

 
