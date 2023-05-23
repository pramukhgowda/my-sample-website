pipeline{
    agent{label 'tomcat'}
    stages{
        stage('cloneorpull'){
            steps{
                git url: 'https://github.com/pramukhgowda/my-sample-website.git', branch: 'master'
            }
        }
        stage('build'){
            steps{
                sh "pwd"
                sh "mvn clean install"
            }
        }
    }
}
