\# Task 8 — Hello Java Maven with Jenkins



This repository contains a simple Java application built with Maven and a Jenkins Freestyle job that builds it.



\## Project Files

\- `src/main/java/HelloWorld.java`

\- `pom.xml`



\## Jenkins Setup

1\. Installed Jenkins via Docker.

2\. Configured Maven (`Maven\_3.9.11`) in \*\*Global Tool Configuration\*\*.

3\. Created Freestyle project linked to this GitHub repo.

4\. Added build step: `clean package`.



\## Output

Jenkins successfully compiles and packages the project:





