pipeline {
    agent any

    tools {
        nodejs 'node'
    }

    stages {
        stage( 'Install dependencies' ) {
            steps {
                echo 'Installing npm dependencies...'
                sh 'npm install'
            }
        }
        stage( 'Build project' ) {
            steps {
                echo 'Build project...'
                sh 'npm run build'
            }
        }
    }
}