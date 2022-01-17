pipeline{
    agent any 
    stages{
        stage('indentifying misconfigs using datree'){
            steps{
                script{
                        withEnv(['DATREE_TOKEN="GJdx2cP2TCDyUY3EhQKgTc"']) {
                              sh 'datree test datree-jenkins.yaml'
                        }

                }
            }
        }
    }

}
