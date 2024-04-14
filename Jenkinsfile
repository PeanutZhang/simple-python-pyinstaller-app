pipeline {
    agent none
    stages {
        stage('Build') {

            steps {
                echo "fffkukuku"
                script {
                    sh 'python -m py_compile sources/add2vals.py sources/calc.py'
                }
            }
        }
    }
}