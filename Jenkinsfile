pipeline {
    agent any
    stages {
        stage('git') {
            steps{
               git branch: 'main', credentialsId: 'git_credentials', url: 'https://gitlab.com/pratik.deshmukh/maven_test.git'
            }
        }
    }
}
