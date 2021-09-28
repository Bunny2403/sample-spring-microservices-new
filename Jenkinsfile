pipeline{

    agent any

    stages{
        stage("Building gateway service"){
            steps{

                sh """ cd gateway-service\
                        
                        mvn package"""

            }

            
        }
    }
}
