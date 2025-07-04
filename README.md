# Custom Alfresco Theme

Make sure you have Maven installed and all dependencies

https://docs.alfresco.com/content-services/latest/develop/sdk/#workingaio

to get started refer to the directions located here to create a style

https://docs.alfresco.com/content-services/latest/tutorial/share/style/

once you have created your project perform

sudo mvn clean

sudo mvn package

please note: the docker content and share modules in the pom are commented out

# Installing on ADP

when the build is done, you have to put the share jar in the share/custom directory in the ADP EC2 folder

restart content(Alfresco) and Share containers

# Installing Jars directly in Tomcat for content and share

copy the jar in hylandtheme-share/target to : /usr/local/tomcat/webapps/share/WEB-INF/lib

then restart both content(Alfresco) and share services

# Using the theme

Now your custom theme will show up in the administration area in ACS. click the drop down and you will see Hyland Theme in the list. Select it and the branding including the login splashpage and logo and other styles will change automatically.

![image](https://github.com/user-attachments/assets/d3a1d8ff-43cc-4dce-a2c4-6be25fbe43fe)
<img width="1057" alt="image" src="https://github.com/user-attachments/assets/e9542d8b-097e-4b92-8369-adfbffe1bde0" />
<img width="1062" alt="image" src="https://github.com/user-attachments/assets/69a01968-298f-44d2-a5ca-ff8306abda9e" />

enjoy!
