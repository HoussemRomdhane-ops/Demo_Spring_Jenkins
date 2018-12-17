#!groovy

stage ('Build')
node ('maven') {
    checkout scm
    sh 'mvn clean package'
}
