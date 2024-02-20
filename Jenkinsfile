pipeline {
    agent {
        label 'Scipt_Slave'
    }
    stages {
        stage ('ShellScript') {
            steps {
                sh '''#!/bin/bash
                sleep 60
                echo "Hello_Scripted_Pipeline"'''
            }
        }
    }
}
