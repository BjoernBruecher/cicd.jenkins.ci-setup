/* Jenkinsfile (Declarative Pipeline) */
pipeline {
    agent any 
    
    stages {
        stage('Source') { 
            steps {
                script {
                    print 'This is source stage step 1...'
                    sleep 2
                    print 'done.'
                }
                script {
                    print 'This is source stage step 2'
                    sleep 2
                    print 'done.'
                }
                script {
                    print 'This is source stage step 3'
                    sleep 2
                    print 'done.'
                }
            }
        }
        
        stage('Build') { 
            steps {
                script {
                    print 'This is build stage step 1...'
                    sleep 2
                    print 'done.'
                }
                script {
                    print 'This is build stage step 2'
                    sleep 2
                    print 'done.'
                }
            }
        }
        
        stage('Test') { 
            steps {
                script {
                    print 'This is test stage step 1'
                    sleep 2
                    print 'done.'
                }
                script {
                    print 'This is test stage step 2'
                    sleep 2
                    print 'done.'
                }
            }
        }
        
        stage('Deploy') { 
            steps {
                script {
                    print 'This is deploy stage step 1'
                    sleep 2
                    print 'done.'
                }
                script {
                    print 'This is deploy stage step 2'
                    sleep 2
                    print 'done.'
                }
            }
        }
    }
}
