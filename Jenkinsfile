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
                docker pull debian
                grype debian:latest
                docker rmi debian:latest
            }
        }
    }
}