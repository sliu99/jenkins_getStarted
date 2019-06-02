stage('Deploy - Staging') {
    steps {
        sh './deploy_staging.sh'
        sh './run-smoke-tests.sh'
    }
}
stage('Deploy - Production') {
    steps {
        sh './deploy_production.sh'
    }
}
