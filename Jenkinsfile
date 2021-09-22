pipeline{
    agent any

    stages{
        stage("config service build"){
            steps{
                echo "Hello World"

                sh """mvn --version\

                cd config-service\

                mvn package\

                cd .."""

                
            }
        }
        stage("department service build"){
            steps{

                sh"""cd department-service\

                mvn package\

                cd .."""
            }
        
        }
    }
}
