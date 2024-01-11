/* Jenkinsfile (Declarative Pipeline) */
pipeline {
    agent any 
    stages {
        stage('Source') { 
            steps {
                print 'This is source stage step 1...'
                sleep 10
                print 'done.'
            }
            steps {
                print 'This is source stage step 2'
                sleep 10
                print 'done.'
            }
        }
        stage('Build') { 
            steps {
                print 'This is build stage step 1...'
                sleep 10
                print 'done.'
            }
            steps {
                print 'This is build stage step 2'
                sleep 10
                print 'done.'
            }
        }
        stage('Test') { 
            steps {
                print 'This is test stage step 1'
                sleep 10
                print 'done.'
            }
            steps {
                print 'This is test stage step 2'
                sleep 10
                print 'done.'
            }
        }
        stage('Deploy') { 
            steps {
                print 'This is deploy stage step 1'
                sleep 10
                print 'done.'
            }
            steps {
                print 'This is deploy stage step 2'
                sleep 10
                print 'done.'
            }
        }
    }
}
