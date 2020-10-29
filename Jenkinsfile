pipeline{

    agent any 


    stages{

        stage('Build'){
            steps{
                echo "Build step" 
            }
        }
        
        stages('Test'){
            steps{
                echo "Test step"
            }
        }

        stages('Deploy'){
            steps{
                echo "Deploy step"
            }
        }
    }
}