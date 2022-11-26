pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/BoDorsaf/MavJen.git'

                // To run Maven on a Windows agent, use
                bat "mvn -version"
		            }

           
            }
        }
    }
