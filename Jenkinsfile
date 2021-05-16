pipeline {

    agent any
    environment { //All defined variables here
        NEW_VERSION = '1.3.0'
    }
    
    stages {
    
        stage("build") {
        
            steps {
                echo 'building the application...'
                echo "building version ${NEW_VERSION}"
                echo "Build number is ${BUILD_NUMBER}"
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
