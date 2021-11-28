# Maven-Learning

maven project set codes



code cmd--- mvn archetype:generate



===========================================
Non Interactive Project Creation command
============================================
code cmd---

 mvn archetype:generate -DgroupId=MyProject 
-DartifactId=DemoMavenProject
-DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false


=============================================
go to the directory of project then type

===========================================

mvn eclipse:eclipse

========================

mvn validate
mvn compile
mvn test
mvn package
mvn install
mvn site
mvn site:run

====================


.m2 folder inside users that will be local repository



==============================================

<properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <maven.compiler.source>1.8</maven.compiler.source>
        <maven.compiler.target>1.8</maven.compiler.target>
</properties>

===========================================

 <!--modern-->
  <properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <maven.compiler.release>15</maven.compiler.release>
  </properties>
  
  
  
  
  
  Stages ---Phases--- Goal
  
  
What are the scopes in Maven?
Maven provides six scopes i.e.
 compile , provided , runtime , test , system , and import