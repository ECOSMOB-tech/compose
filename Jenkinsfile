#!groovy_script
node{
  stage('checkout code'){
    git url:'',branch:'main'
  }
  stage('run container'){
    sh 'docker-compose config'
    sh 'docker-compose up -d'
  }
}
  
    
  
  
