pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
                // Now 'steps' is valid here
                git url: 'https://github.com/Mohankumarc1/Simplybyte_calculator.git',
                    credentialsId: 'github-checkout-creds', // Substitute your Jenkins Credential ID
                    branch: 'main'
            }
        }
    }
}
