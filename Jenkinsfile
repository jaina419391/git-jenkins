"#!/usr/bin/env/ groovy

import hudson.model.*
import hudson.EnvVars
import java.net.URL

node{
    stage('Git Checkout'){
        git 'https://github.com/ajain19391/DevOpsClassCodes.git'
    }
    stage('Compile'){
        sh 'mvn compile'
    }
    stage('Package'){
        sh 'mvn package'      
    }
}"
