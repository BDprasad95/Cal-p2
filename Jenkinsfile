pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/BDprasad95/java-rest-api-calculator-1.git'
                sh ' ./mvn clean compile '
            }
        }
        stage('test'){
            steps{
                sh './mvn test'
                
            }
        }
    }
}
