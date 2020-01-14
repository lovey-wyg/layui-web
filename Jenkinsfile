pipeline {
    // 执行pipeline
    agent any
    // 常量参数
    environment{
        PROJECT_NAME = 'web-im'
    }
    // 结果通知
    post{
        success{
            script {
                echo env.TAG_NAME
            }
        }
        failure{
            script {
                echo env.TAG_NAME
            }
        }
        unstable{
            script {
                echo env.TAG_NAME
            }
        }
    }
    // pipeline各个场景
    stages {
        stage('Prepare'){
            steps{
                echo "Prepare start ---"
                script{
                    echo env.TAG_NAME
                }
                echo "Prepare finish ---"
            }
        }
        stage('Build'){
            steps{
                echo "Build start ---"
                script{
                    echo env.TAG_NAME
                }
                echo "Build finish ---"
            }
        }
        stage('Test'){
            steps{
                echo "Test start ---"
                script{
                    echo env.TAG_NAME
                }
                echo "Test finish ---"
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploy start ---"
                script{
                    echo env.TAG_NAME
                }
                echo "Deploy finish ---"
            }
        }
    }
}
