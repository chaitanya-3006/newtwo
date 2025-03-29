pipeline{
  agent any
  tools{
    nodejs "node"
}
stages{
  stage('Checkout'){
    steps{
    bat scm
  }}
  stage('Test'){
    steps{bat 'npm install'
    bat 'npm test'
    echo 'test not defined'
  }}
  stage('Build'){
    steps{bat 'npm run build'
  }}
}
}
