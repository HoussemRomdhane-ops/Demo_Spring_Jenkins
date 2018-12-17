#!groovy
@Library('jenkins-pipeline-library@Dev')
import hudson.model.*
stage ('Build')
node ('maven') {
    checkout scm
    initCICD()
    sh 'mvn clean package'
}
