pipeline{
    agent any
    stages{
        stage('install nginx'){
            steps{
                sh 'apt install nginx -y'
            }
        }    
        stage('deploy index'){
            steps{
                sh '''
                echo "Welcome to this automated pipeline..." >> /var/www/html/index.html
                '''
            }
        }    
        
    }
}