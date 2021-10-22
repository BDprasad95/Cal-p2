pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/BDprasad95/java-rest-api-calculator-1.git'
                sh ' ./mvnw clean install compile '
            }
        }
        stage('test'){
            steps{
                sh './mvnw test'
                
            }
        }
    }
}
