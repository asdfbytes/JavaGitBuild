pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/asdfbytes/JavaGitBuild.git'
            }
        }
        stage('Build'){
            steps{
                bat 'javac Demo.java'
            }
        }
       stage('Execute'){
            steps{
                bat 'java Demo'  
    }
}
}
}
