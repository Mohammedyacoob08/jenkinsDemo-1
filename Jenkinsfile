pipeline 
{
    agent any

    stages
    {
        stage('build') 
        {
            steps 
            {
                echo 'build app'
            }
        }

        stage('test') 
        {
            steps 
            {
                echo 'test app'
            }
        }
        stage('deploy') 
        {
            steps 
            {
                echoo 'deploy app'
            }
        }
    }
    post
    {
         always
        {
            emailext body: 'summary', subject: 'pipeline status', to: 'nadeem81299@gmail.com'
        }
    }
}
