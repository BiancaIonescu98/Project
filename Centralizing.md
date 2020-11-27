# Project
Here is a project with an centralizing for java exercises
I used gui because in this centralizing I forward the program to the next exercises just when I push F10 and backforward when I push F9. In every subfolder with exercises I have an XML file with this components :
<?xml version="1.0" encoding="UTF-8"?>

<params>
	<setParameter name = "idx" value = "0"/>
	<setParameter name = "title" value = "Application with animals"/>	
	<!-- optional use "description" attribute instead for shorter thingies -->
	<setParameter name = "description_file" value = "init.xml"/>
	<setParameter name = "description" value = "Show what animals can do"/>	
</params>

My program read the xml and make a print in gui window.
