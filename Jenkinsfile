pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Compile the HelloWorld.java file using javac (if you're not using Maven)
                script {
                    bat 'python Program.py'
                }
            }
        }

        stage('Test') {
            steps {
                // Run unit tests (if using Maven, this would be part of the build)
                script {
                    bat 'python Program.py '  // Run the compiled HelloWorld class
                }
            }
        }
    }
}
