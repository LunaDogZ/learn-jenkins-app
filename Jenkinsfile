pipeline {
    agent {
        docker {
            image 'node:18-alpine' 
            reuseNode true  // สำคัญ! ใช้เพื่อแชร์ Workspace เดิม
        }
    }
    stages {
        stage('Test Configuration') {
            steps {
                sh 'npm --version'
                sh 'node --version'
            }
        }
    }
}