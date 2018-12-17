#!groovy

stage ('Build')
node ('maven') {
    checkout scm
    mvn 'clean package'
}
