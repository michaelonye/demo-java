pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('Build') {
            steps {
                
                git 'https://github.com/michaelonye/demo-java.git'

                // Run Maven on a Unix agent.
                sh "mvn clean package"

                
            }
         
            
            }
        }
}

 
