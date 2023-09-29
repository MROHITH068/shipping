pipeline
{
    agent{
        node {label 'workstation'}
    }

    stages{
        stage('Build'){
            steps{
             echo 'mvn package'
            }
        }

        stage('Unit tests'){
            steps{
             echo 'Unit tests'
            }
        }

        stage('Code Analysis'){
            steps{
             echo 'Code Analysis'
            }
        }

        stage('Publish a Artifact'){
            steps{
             echo 'Publish a Artifact'
            }
        }


        stage('Publish a Artifact'){
            steps{
             echo 'Publish a Artifact'
            }
        }
    }
}