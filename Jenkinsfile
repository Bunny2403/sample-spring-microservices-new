pipeline{
    agent any

    stages{
        stage("build"){
            steps{
                echo "Hello World"

                sh "mvn --version"

                sh "cd config-service "

                sh "mvn package"

                sh "cd .."

                
            }
        }
    }
}
