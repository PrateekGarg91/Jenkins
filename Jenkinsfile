pipeline { 
    agent any
    stages {
        stage('Clone Git') {
            steps {
                git 'https://github.com/PrateekGarg91/Jenkins.git'
            }
        }
        stage('Build Code') {
            steps {
                sh "chmod u+x Prog1.py"
                sh "./Prog1.py"
            }
        }
     stage('Test Code') {
            steps {
                sh "chmod u+x Test.py"
                sh "./Test.py"
            }
        }
        stage('Deploy'){
            steps{
                sh "chmod u+x a.c"
                sh "gcc a.c"
                sh "./a.out"
            }
        }
    } 
}
