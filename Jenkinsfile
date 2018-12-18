#!groovy
@Library('jenkins-pipeline-library')
import hudson.model.*

def dummy
maven {
    ws ('pipelines'){
        git 'http://gogs-iamp.pathfinder.gov.bc.ca/iamp/jenkins-pipeline-library.git'

        def pipeline = load 'testpipeline.groovy'

        
        pipeline.tagDownstreamRepos()
    }
}
