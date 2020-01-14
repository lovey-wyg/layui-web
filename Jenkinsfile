pipeline {
    // 执行pipeline
    agent any
    // 常量参数
    environment{
        PROJECT_NAME = 'web-im'
    }
    options {

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

            }
        }
        unstable{
            script {

            }
        }
    }
    // pipeline各个场景
    stages {
        stage('Prepare'){
            steps{
                echo "Prepare start ---"
                script{

                }
                echo "Prepare finish ---"
            }
        }
        stage('Build'){
            steps{
                echo "Build start ---"
                script{

                }
                echo "Build start ---"
            }
        }
        stage('Test'){
            steps{
                echo "Test start ---"
                script{

                }
                echo "Test start ---"
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploy start ---"
                script{

                }
                echo "Deploy start ---"
            }
        }
    }
}
