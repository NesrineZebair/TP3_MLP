pipeline {
    agent any
    
    stages {
      stage('build from github'){
        steps {
            echo "fetch code " 
            echo " build code " 
        }
      }
      stage('test from github'){
          steps{
              echo 'running test1'
              echo 'running test2'
              echo 'pip install flask'
              echo 'python -m flask run'
          }
      }
  }
  
}
