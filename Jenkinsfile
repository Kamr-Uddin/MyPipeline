pipeline {
    agent any
    stages {
        stage("Build1") {
            steps {
                echo "Stage 1: Building BWCE app..."
            }
        }
        stage("Test1") {
            steps {
                echo "Stage 2: Testing the BWCE app..."
            }
        }
        stage("Deploy1") {
            steps {
                echo "Stage 3: Deploying the BWCE app..."
                sh '''
                    echo "This block contains multi-line steps"
                    ls -lh
                '''
            }
        }
    }
    post {
        cleanup {
            echo "Cleaning the workspace"
            cleanWs()
        }
    }
}
