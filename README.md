# ClipsWithJava
A sample clips with java application with a demo HTML page to add fact and retrieve facts. Can add rules by using clips.build() function where ever required.

Clips JNI download :
https://sourceforge.net/projects/clipsrules/files/CLIPS/6.40_Beta_1/clips_jni_640.zip/download  and paste the clipsJNI.dll file from download location\clips_jni_640\CLIPSJNI to system32 folder under C:\Windows

#How to make it work ?

1. Download the war file
2. Import in eclipse
3. Download tomcat server, from https://tomcat.apache.org/download-90.cgi
4. Add the server via server tab in eclipse
5. Add the application "SampleClipsJava" to the server
6. Deploy the application and see the output in the browser

Bingo !! There you go.. 

7. Place all your rules and templates in rules.clp and template.clp file under webcontent/web-inf/ClipsSources
8. Refeer to myscripts.js file to make GET and POST ajax request to add and retrive facts.


PRIOR KNOWLEDGE NEEDED = Java Servlets, REST requests, JQuery AJAX
