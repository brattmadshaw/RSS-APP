pipeline {
    agent any

    environment {
        CUSTOM_NETWORK = 'my_app_network'
    }

    stages {
        stage('Setup Custom Network and remove existing containers') {
            steps {
                script {
                    
                    
                }
            }
        }

        stage('Start MySQL') {
            steps {
                script {
                    // Run mysql 5.7 container passing through environment vars for MYSQL_ROOT_PASSWORD(rootpassword), MYSQL_DATABASE, MYSQL_USER and MYSQL_PASSWORD(check source code for correct values). Consider the container name and custom network. 
                    
                    // Wait for MySQL to fully start - add a delay of 10 seconds:
                    
                }
            }
        }

        stage('Build and Run Backend') {
            steps {
                script {
                    // Navigate to the backend directory
                    dir('backend') {
                        // Build the Docker image for the backend
                        
                        // Run the backend container in the custom network and consider the container name and ports (look in source code).
                        
                    }
                }
            }
        }

        stage('Build and Run Frontend') {
            steps {
                script {
                    // Navigate to the frontend directory
                    dir('frontend') {
                        // Build the Docker image for the frontend
                        
                        // Run the frontend container in the custom network considering the ports.
                        
                    }
                }
            }
        }
    }
}
