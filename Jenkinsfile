pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                // Clone the GitHub repository
                bat 'git clone https://github.com/OmerMeister/GitExercise.git'

                // Run the Python script
                bat 'python your-script.py'
            }
        }
    }
}