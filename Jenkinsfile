pipeline {
    agent any 
    stages {
        stage('Bulid') {
            steps {
                echo 'Built'
            }
        }
         stage('Test') {
            steps {
                echo 'Tested !' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Successfully Deployed !' 
            }
        }
        
    }
    post{
        always{
            echo 'Success or Failure'
        }
        success{
            echo 'Success'
        }
        failure{
                echo 'Failure'
            }
        }
    
}
