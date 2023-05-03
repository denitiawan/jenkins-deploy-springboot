# learn-jenkins-deploy-springboot
learn deployment springboot app using jenkins



![image](https://user-images.githubusercontent.com/11941308/235840875-3b2a7a7c-90c6-4f36-8448-6bd2ec0c3d88.png)


### Clone Repo
- Jenkins will clone repository to github
- jenkins will save the repo into folder jenkins_home/workspace/[repository name]

### Build Project
- jenkins will open folder jenkins_home/workspace/[repository name]
- jenkins will run syntax "mvn clean install" 
- and then .jar already created

### Build Docker Image
- jenkins will open folder jenkins_home/workspace/[repository name]
- jenkins will run syntax "docker build ."
- and then docker image alreadey created

### Deploy Docker Image
- jenkins will run syntax "docker run container .... image:image name"
