pipeline{
    agent any 
    stages{
        stage('indentifying misconfigs using datree'){
            steps{
                script{
                       
                              sh 'datree config set token GJdx2cP2TCDyUY3EhQKgTc '
                              sh 'datree test datree-jenkins.yaml'
                }
            }
        }
    }

}
