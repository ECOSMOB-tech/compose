#!groovy_script
node{
  stage('checkout code'){
    git url:'https://github.com/ECOSMOB-tech/compose.git',branch:'main'
  }
  stage('run container'){
    sh 'docker rmi -f nginx'
    sh 'docker stop nginxserver'
    sh 'docker rm -f nginxserver'
    sh 'docker-compose config'
    sh 'docker-compose up -d'
  }
}
  
    
  
  
