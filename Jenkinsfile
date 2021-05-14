pipeline {

    agent any
    
    stages {
    
        stage("build") {
        
            steps {
                 sh "ls -la ${pwd()}"
            }
        }
        
        stage("test") {
        
            steps {
                echo 'testing the application...'
            }
        }
        
        stage("deploy") {
        
            steps {
                echo 'deplying the application...'
            }
        }
    }
}
