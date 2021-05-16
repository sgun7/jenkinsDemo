def gv

pipeline {

    agent any
    environment { //All defined variables here
        NEW_VERSION = '1.3.0'
    }

    tools {
        maven 'Maven'
    }
    
    stages {
    
        stage("init") {
           steps {
               script {
                    gv = load "script.groovy"
               }
           }
        }
        stage("build")
        {
            steps
            {
                script 
                {
                    gv.buildApp()
                }
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
