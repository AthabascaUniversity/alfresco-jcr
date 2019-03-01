
Alfresco removed JCR Repository (JSR-170) support from Alfresco in version 5 onwards.

This is a Maven based project to build an AMP file which can be used to attempt to restore that old JCR implementation into a newer version of Alfresco.

This project contains an export of the following code from the Alfresco 4.2 SVN:

https://svn.alfresco.com/repos/alfresco-open-mirror/alfresco/COMMUNITYTAGS/V4.2f/root/license.txt -> /license.txt
https://svn.alfresco.com/repos/alfresco-open-mirror/alfresco/COMMUNITYTAGS/V4.2f/root/projects/repository/source/java/org/alfresco/jcr -> /src/main/java/org/alfresco/jcr
https://svn.alfresco.com/repos/alfresco-open-mirror/alfresco/COMMUNITYTAGS/V4.2f/root/projects/repository/config/alfresco/jcr-api-context.xml -> /src/main/amp/config/alfresco/module/alfresco-jcr/context/jcr-api-context.xml
https://svn.alfresco.com/repos/alfresco-open-mirror/alfresco/COMMUNITYTAGS/V4.2f/root/projects/repository/config/alfresco/model/jcrModel.xml -> /src/main/amp/config/alfresco/module/alfresco-jcr/model/jcrModel.xml

I am in no way affiliated with Alfresco and this project comes with no support or warranty of any kind. USE AT YOUR OWN RISK. All praise the LGPL.
