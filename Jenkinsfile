pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                // Clone the GitHub repository
                bat 'git clone https://github.com/OmerMeister/GitExercise.git.git'

                // Install Python dependencies (if required)
                bat 'pip install -r requirements.txt'

                // Run the Python script
                bat 'python your-script.py'
            }
        }
    }
}