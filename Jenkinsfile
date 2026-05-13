pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        sh 'docker build'
        
      } 
    }
    stage('test'){
          steps{
            sh 'docker test'
          }
    }
    stage('deploy'){
          steps{
            sh 'docker deploy '
          }
            
    }
  }
}
