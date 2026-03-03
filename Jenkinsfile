pipeline{
        agent any
        stages{
                stage('Build'){
                         steps{
                                echo "Buildmyweb"
                        }                     
                }
        stages{
                stage('run sample'){
                        steps{
                                bat 'sample.py'
                        }
                }
        }
}
