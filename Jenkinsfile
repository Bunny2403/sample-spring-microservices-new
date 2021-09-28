pipeline{

    agent {
        label 'nod1'
        
    }

    stages{
        stage("Building gateway service"){
            steps{

                sh """ cd gateway-service\
                        
                        mvn package"""

            }

            
        }
    }
}
