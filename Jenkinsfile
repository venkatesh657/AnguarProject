pipeline{
    agent{
        label "demonode"
    }
    stages{
        stage('checkout'){
            steps{
                checkout scm
            }
        }
        stage('successfully execution'){
            steps{
                echo "checkout has been done."
            }
        }
    }
}