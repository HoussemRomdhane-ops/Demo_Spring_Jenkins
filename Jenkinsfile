#!groovy
@Library('jenkins-pipeline-library-multibranch')
import hudson.model.*
stage ('Build')
node ('maven') {
    checkout scm
    initCICD()
    sh 'mvn clean package'
}
