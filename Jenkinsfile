pipeline{
  agent any
  tools{
    nodejs "node"
}
stages{
  stage('Checkout'){
    bat scm
  }
  stage('Test'){
    bat 'npm install'
    bat 'npm test'
    echo 'test not defined'
  }
  stage('Build'){
    bat 'npm run build'
  }
}
  
