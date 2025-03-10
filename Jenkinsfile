pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('Clean'){
            steps{
                sh 'mvn clean '
            }
        }
        stage('Build'){
            steps{
                echo "mvn package"
                echo "hello"
        }
    }
    }
}
