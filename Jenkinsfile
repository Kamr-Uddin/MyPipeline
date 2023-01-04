pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo "Stage 1: Building BWCE app..."
            }
        }
        stage("Test") {
            steps {
                echo "Stage 2: Testing the BWCE app..."
            }
        }
        stage("Deploy") {
            steps {
                echo "Stage 3: Deploying the BWCE app..."
                sh '''
                    echo "This block contains multi-line steps"
                    ls -lh
                '''
            }
        }
    }
}
