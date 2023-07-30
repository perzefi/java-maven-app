pipeline {
    agent any
    stages {
        stage("build"){
            steps {
                    echo "Buidling the application..."
            } 
        }
        stage('test') {
            steps {
                echo "Testing the application..."
            }
        }
        stage('deploy') {
            steps {
               echo "Deploying the application..."
            }
        }
    }
}
