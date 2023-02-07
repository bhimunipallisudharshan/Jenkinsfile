pipeline{
    agent{
        node{
            label "javabuildserver2"
        }
    }
    stages{
        stage('print'){
            steps{
                git branch: 'main', credentialsId: '2b1c00cf-2a02-4a7c-be83-2bf9ccc2ec88', url: 'https://github.com/bhimunipallisudharshan/twitterland.git'
            }
        }
        stage('hello world'){
            steps{
                git credentialsId: '2b1c00cf-2a02-4a7c-be83-2bf9ccc2ec88', url: 'https://github.com/ravdy/hello-world.git'
            }
        }
        stage('nodejs'){
            steps{
                git credentialsId: '2b1c00cf-2a02-4a7c-be83-2bf9ccc2ec88', url: 'https://github.com/ravdy/nodejs-demo.git'
            }
        }
        stage('valaxy var rtp'){
            steps{
                git branch: 'main', credentialsId: '2b1c00cf-2a02-4a7c-be83-2bf9ccc2ec88', url: 'https://github.com/ravdy/valaxy-rtp.git'
            }
        }    
        }
    }

