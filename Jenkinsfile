pipeline{
    agent any
        stages{
            stage('clone')
            {
                steps
                {
                    git branch:'main',url :'https://github.com/prathyushadyaka77/devops.git/'
                }
            
            }
            stage('build')
            {
                steps
                {
                    sh 'javac Hello.java'
                }
            }
            stage('run')
            {
                steps
                {
                    sh 'java Hello'
                
            }
        }
    }
}
