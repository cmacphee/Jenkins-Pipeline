pipeline{
        agent any
        stages{
              stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file3 "
                }
            }  
//            stage('Clone repo'){
//                steps{
//                    sh "git clone https://gitlab.com/qacdevops/chaperootodo_client.git"
//                }
//            }
//             stage('Install Docker/Docker-compose'){
//               steps{
//                    sh "curl https://get.docker.com | sudo bash"
//                }
//            }
//            stage('Install Docker/Docker-compose'){
//                steps{
//                   sh 'sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose'
//                }
//            }
//            stage('Deploy App'){
//                steps{
//                    sh "sudo docker-compose pull && sudo -E DB_PASSWORD=${DB_PASSWORD} docker-compose up -d"
//                }
//            }
        }
}
