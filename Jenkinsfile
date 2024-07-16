pipeline{
    agent any
    stages{
      /*  stage('Make directory'){
            steps{
                sh "mkdir ~/jenkins-tutorial-test || true"
                sh echo 'Directory has been made'
            }
        stage('make files'){
            steps{
                sh "touch ~/jenkins-tutorial-test/file1"
                sh echo 'file1 has been made'
            }
        } */

        stage('run script'){
            steps{
                sh 'chmod +x ./deploy.sh'
                sh './deploy.sh'
            }
        }
    }
}
