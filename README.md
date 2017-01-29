
#Tutorial: configure project using XML file <br />
#Content: show how to configure a project using XML file in Spring Framework <br />
#Date created: Friday 27 Jan 2017 <br />                                      
#Author: Dinh Duc <br />                        
#Coppyright © Spring Community <br />                         
#Link group : https://www.facebook.com/groups/1811052582478351/ <br />


#Create Maven project using command 
<quote>
mvn archetype:generate
mvn eclipse:eclipse
</quote>
#Copy dependencies to the POM file and then use Maven to update project
<quote>
    spring-context
    spring-webmvc
    javax.servlet-api
    javax.inject
</quote>
#Create applicationContext.xml in webroot







