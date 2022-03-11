node{
  stage('Checkout'){
    checkout scm  
  }
  stage('Build Image'){
    sh "docker build -t my-goapp-image ."
  }
}
