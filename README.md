# Face-Recognition-for-providing-security-using-Deep-learning
This is a Project on maintaining Security in Bank Lockers or at any system using Face Recognition using Deep Learning

--------------------------------------
Download the files and create the virtual environment for the project.
Then in activated virtual environment install all the requirememts as mentioned in requirement.txt file.
--------------------------------------
Manually add about 500 images not containing human faces at all like that of mountains, flowers, and many other of these types in application>database>images>00not folder.
Then for commecting the system with database install mysql and make migrations for the views.models in django.
--------------------------------------
Now create the superuser as an first admin ad an entry of the auth table in django. While other admins can be created from within the Web App.
Now run the server after going in that application folder.
--------------------------------------
Now on login page use superadmin email and password to log in.
After clicking to add user option the dataset will be taken and model will start training at that time after dataset being taken.
--------------------------------------
At the end the User will be able to login with proper recognition of their face.
