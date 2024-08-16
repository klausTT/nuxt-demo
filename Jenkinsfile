pipeline {
    agent {
        docker {
            image 'oven/bun:latest'
        }
    }
    stages {
        stage('Install Dependencies') {
                steps {
                    // 使用 bun 安装依赖
                    sh 'bun install'
                }
        }

        stage('Build') { 
            steps {
                // 
                echo "hello Build"
            }
        }
        
        stage('Deploy') { 
            steps {
                // 
                echo "hello Deploy"
            }
        }
    }
}