pipeline{
  agent any
  stages{
    stage('checkout'){
      steps{
        git "https://github.com/ruhi14547/SecondAssignment.git"
      }
    }
    stage('Build'){
      steps{
        echo "Building Application"
        bat 'javac javacode.java'
      }
    }
    stage('Deploy'){
      steps{
        echo "Deploying Application"
        bat 'java javacode'
      }
    }
} 
