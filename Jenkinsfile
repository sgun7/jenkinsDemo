pipeline {

    agent any
    
    stages {
    
        stage("build") {
        
            steps {
                echo 'building the application...'
                sh "ls"
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
