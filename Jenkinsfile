pipeline{
  agent any
  stages{
    stage('checkout'){
      steps{
        git "https://github.com/ruhi14547/SecondAssignment.git"
      }
    }
    stages{
    stage('Build'){
      steps{
        echo "Building Application"
        bat 'javac javacode.java'
      }
    }
      stages{
    stage('Deploy'){
      steps{
        echo "Deploying Application"
        bat 'java javacode'
      }
    }
    
