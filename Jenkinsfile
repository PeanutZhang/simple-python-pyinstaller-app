pipeline {
    agent none
    stages {
        stage('Build') {

            agent  { none 'python:3.9' }
            steps {
                echo "fffkukuku"
                script {
                    sh 'python -m py_compile sources/add2vals.py sources/calc.py'
                }
            }
        }
    }
}