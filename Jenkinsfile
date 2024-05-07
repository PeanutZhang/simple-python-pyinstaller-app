pipeline {
    agent any

    stages {

        stage('Stage 1'){

        steps {

         echo 'Hello World'
         echo '=========================================='
         echo "env.workspece =  ${env.WORKSPACE}"
         
        }

        }

        stage('print env info'){

            steps {
                echo '+++++++++++++++++++++++++++++++++++'
                echo "env.branchName =${env.BRANCH_NAME}"
                echo "env.BUILD_ID = ${env.BUILD_ID}"
                echo "evn.path= ${env.PATH}"
                echo "env.BUILD_NUMBER = ${env.BUILD_NUMBER}"
                echo   "env.JOB_NAME = ${env.JOB_NAME}"
                echo "env.JENKINS_HOME= ${env.JENKINS_HOME}"
                echo "env.JENKINS_URL = ${env.JENKINS_URL}"
                echo "env.build_url= ${env.BUILD_URL}"


            }

        }

    }

}