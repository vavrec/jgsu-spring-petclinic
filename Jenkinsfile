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
                bat 'cd'
            }
        }
    }
        post {
            success {
                // we only worry about archiving the jar file if the build steps are successful
                archiveArtifacts(artifacts: '**/target/*.jar', allowEmptyArchive: true)
                }
            }
}