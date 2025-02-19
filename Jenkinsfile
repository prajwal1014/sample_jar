pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('clean'){
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
