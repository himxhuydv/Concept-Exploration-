# Object detection 
So,basically the object detection is based on the two factor.
1.What object are present(Classification)?
2.Where are they located(Localization)?
*let's go more deep what does it mean what object are present?(classification).*
# Classification:it mean what object is present or we can say which labeled is present in to the specific area.
this is one of the fundamental part of object detection is created on.
So,basically it's assinging the model a label but how does the model is assigning a label to the class of object by it's own.
**My question is simple how does the  model is understanding the human sense if we give it the  numebr how does it understanding this is the phone number,**
Scenario:If we give a photo of the cat to the object detection.
Object detetion :will answer it "this is a cat." 
**How does it understanding every pixel represent this class or this object(cat)?**
So,Understand through CNN what it does is extract all the feature from the photo do complex mathematical operation on it.
At,First it's start takes input from the images (which basically is extracted feature from the images.->CNN) in the segmenated form.then,every layer's do complex mathematical operation on that extracted feature and then matched it to the present labeled traning data.if it's get matched it's mean that particular pixel belong to the specific labeled class.**(most important part)*each layer take input then do the mathematical operation on it then give output to the next layers.so that theyc an ***