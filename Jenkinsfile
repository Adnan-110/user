@Library('Jenkins-Shared-Library') _ 

pipeline{
    agent{
        label 'ws'
    }
    stages{
        stage('Lint Checks') {
            steps {
                script{
                    helloWorld.info("User")
                    nodeJs.lintChecks()
                }
            }
        }
        stage('Static Code Analysis') {
            steps{
                sh "echo ****** Starting Static Code Analysis ******"
            }   
        }
    }
}