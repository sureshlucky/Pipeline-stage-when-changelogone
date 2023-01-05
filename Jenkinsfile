pipeline{
    agent any
    stages{
        stage("BUILD") {
            when {
                changelog '.*sometext'
            }
            steps{
                echo "Hello World Chngelog"
            }
        }
    }
}
