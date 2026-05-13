pipeline{
  agent any
  stages{
    stage('hello'){
      steps{
        echo "demo of pi[eline from poll scm"
        echo "made changes"
        sh 'git pull origin master'
        sh 'cat file1'
        
      }
      
      
    }
  }
}
