pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('Code Clone') {
            steps {
                // Get some code from a GitHub repository
                git 'git@github.com:lksingh009/newrepo.git'
            }

            
            }
            
            stage('Check Artefact') {
            steps {
                echo 'This is my Hello Job'
                
            }

            
            }
        }
    }
}




