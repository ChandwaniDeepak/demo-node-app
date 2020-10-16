pipeline {
    agent any
    
    
    stages{
        stage(" install "){
            echo "Installing node project"
            sh 'npm install'
        },
        stage(" build "){

        },
        stage(" run "){
            echo "running node project"
            sh 'node src/index.js'
        }
    }
    
}