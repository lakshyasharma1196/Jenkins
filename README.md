# Jenkins

Jenkins is an open-source automation server that is widely used for building, testing, and deploying software projects. It provides a platform for automating various tasks associated with the software development and delivery process.

1. Automation Server

2. Continuous Integration (CI) and Continuous Delivery (CD):

3. Extensible and Customizable

4. Integration with Version Control

# Jobs

1. Freestyle Project

2. Pipeline 

3. Multi-Configuration Project:

4. Folder

5. GitHub Organization 

6. Multibranch Pipeline

# Run Jenkins through docker

```
docker run -p 8080:8080 -p 50000:50000 --restart=on-failure -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk11
```

# Pipeline Syntax

```
pipeline {
    /* insert decalarative pipeline here*/
    agent any
    stages{
        stage("Demo"){
            steps{
                  echo "Hello Jenkins"
            }
        }
    }
}
```


