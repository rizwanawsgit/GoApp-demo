node{
  stage('Checkout'){
    checkout scm  
  }
  stage('Build Image'){
    sh "docker build -t my-goapp-image ."
    sh "docker container run -d -p 8080:8080 my-goapp-image"
  }
}
