#!groovy_script
node{
  stage('checkout code'){
    git url:'https://github.com/ECOSMOB-tech/compose.git',branch:'main'
  }
  stage('run container'){
    sh 'docker-compose config'
    sh 'docker-compose up -d'
  }
}
  
    
  
  
