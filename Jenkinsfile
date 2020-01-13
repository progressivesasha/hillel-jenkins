#!/bin/env groovy

node {
    deleteDir()
    
    properties([buildDiscarder(logRotator(numToKeepStr: '100'))])
    
    sh 'echo Hello World!'
}
