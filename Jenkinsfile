pipeline{
    agent any
    tools{
        nodejs "node"}
     stages{
    stage('Checkout'){
        steps{
            script{
                echo "Checking"
                checkout scm
            }
        }
    }
    stage('Test'){
        steps{
            script{
                echo "Running"
                bat 'npm test'
            }
        }
    }
    stage('Build'){
        steps{
            script{
                bat 'npm install'
            }
        }
     }
}
}
