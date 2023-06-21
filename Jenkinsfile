pipeline 
{
    agent any
    
    stages 
    {
        stage('compile') {
            steps {
               build 'compile'
            }
        }
        stage('test') {
            steps {

               build 'test'
            }
        }
        stage('package') {
            steps {

                build 'package'
            }
         }
        stage('container-deployment')
        {
            steps{
                build 'container-deployment'
            }
        }
       
    }
        
    }
