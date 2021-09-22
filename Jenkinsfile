pipeline{
    agent any

    stages{
        stage("build"){
            steps{
                echo "Hello World"

                sh """mvn --version\

                cd config-service\

                mvn package\

                cd .."""

                
            }
        }
    }
}
