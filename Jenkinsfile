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
        stage('build'){
            steps{
                sh 'mvn package'
        }
    }
