pipeline{

    agent any 


    stages{

        stage('Build'){
            steps{
                echo "Build step" 
                bat 'mvn package'
            }
        }
        
        stage('Test'){
            steps{
                echo "Test step"
                bat 'mvn test'
            }
        }

        stage('Deploy'){
            steps{
                echo "Deploy step"
                bat 'pwd'
            }
        }
    }
}