pipeline {
    agent { label 'java' }
    stages {
        stage('checkout') { 
            steps {
              parallel(
              a: {
              sh 'echo “welcome to devops”'
            },
              b: {      
              sh 'echo “good morning”'
            },
              c: {      
              sh 'echo “hello hello”'
            }
          )     
       }
    }
  }
}
