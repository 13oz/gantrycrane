pipeline 
{
    agent any 
    stages 
    {
        stage('Stage 1') 
        {
            steps 
            {
                echo 'Hello world!' 
            }
        }
        stage('Docker pull')
        {
            steps
            {
                sh 'docker pull debian'
                sh 'grype debian:latest'
                sh 'docker rmi debian'
            }
        }
    }
}