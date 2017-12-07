#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/Demo-projectt/repo1.git'],
    pipelineTriggers([
       upstream(
      threshold: 'SUCCESS',
      upstreamProjects: 'https://github.com/Demo-projectt/repo2.git'
    )])

node {
   stage 'build'
   echo 'hello boy'
   stage 'test'
   echo 'bomb'
    stage 'deploy'
    echo 'avengers'
}
