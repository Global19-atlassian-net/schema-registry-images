#!/usr/bin/env groovy

dockerfile {
    dockerPush = true
    dockerRepos = ['confluentinc/schema-registry',]
    mvnPhase = 'package'
    mvnSkipDeploy = true
    nodeLabel = 'docker-oraclejdk8-eli-compose'
    slackChannel = 'tools' //TODO: change to correct team
    upstreamProjects = [] //TODO: after roll out, this will be the packaging job
    dockerPullDeps = ['confluentinc/cp-base-new']
    usePackages = true
}
