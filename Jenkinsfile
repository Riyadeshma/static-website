pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                sh 'rm -rf static-website '
             sh'    git clone https://github.com/Riyadeshma/static-website.git static-website'
            }
        }
        stage('deploy'){
            steps{
                sh 'sudo cp -r * /var/www/html/'
                
            }
        }
    }
}
