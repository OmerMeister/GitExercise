pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/OmerMeister/GitExercise.git'
      }
    }

    stage('Run Python Script') {
      steps {
        sh 'python main.py'
      }
    }
  }
}