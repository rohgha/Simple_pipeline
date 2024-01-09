# Simple_pipeline
script


pipeline
{
    agent any
    
    stages{
        stage('build')
        {
            steps{
                echo "Build activity"
            }
        }
        stage('test')
        {
            steps{
                echo "Test artifacts"
            }
        }
        stage('deploy')
        {
            steps{
                echo "Deploy the artifacts"
            }
        }
    }
}

