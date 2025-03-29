pipeline{
  agent any
  tools{
    nodejs "node"
}
stages{
  stage('Checkout'){
    Steps{
    bat scm
  }}
  stage('Test'){
    Steps{bat 'npm install'
    bat 'npm test'
    echo 'test not defined'
  }}
  stage('Build'){
    Steps{bat 'npm run build'
  }}
}
}
