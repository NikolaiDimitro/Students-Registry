pipeline{
    agent{
        label any
    }
    stages{
        stage("Install dependencies"){
                echo "========installing dependencies========"
            steps{
                bat "npm install"
            }
        }
        stage("Run UI tests"){
            steps{
                bat "npm test"
            }
        }
    }
}