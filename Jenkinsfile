pipeline{
    agent any
    stages{
        stage(build){
            steps{
                echo "this is a demo"
                sh 'ls -lh'
            }
        }
        stage(test){
            steps{
                sh 'pwd'
            }
        }
        stage(deploy){
            steps{
                sh 'whoami'
            }
        }
    }
}
    
