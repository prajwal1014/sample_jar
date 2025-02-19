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
                sh 'mvn package'
        }
    }
    }
}
