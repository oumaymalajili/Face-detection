# Face-detection
FaceDetection with numpy and opencv  
*You can use Google to find various Haar Cascades of things you may want to detect. You shouldn't have too much trouble finding the aforementioned types. We will use a Face cascade and Eye cascade. You can find a few more at the root directory of Haar cascades. Note the license for using/distributing these Haar Cascades.
*The creation of faces :
Steps : 
For more information, visit the documentation for the detectMultiScale functionality. Basically, it finds faces! We also want to find eyes, but, in a world of false positives, wouldn't it be prudent to logically make it so that we only find eyes in faces? Let's hope we're not looking for eyes that aren't in faces! In all seriousness, "eye detection" probably wouldn't find an eyeball laying around. Most eye detection uses the surrounding skin, eye lids, eye lashes, and eye brows to also make the detection. Thus, our next step is to break down the faces first, before getting to the eyes. 
