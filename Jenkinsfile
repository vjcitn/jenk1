pipeline {
    agent { docker { image 'bioconductor/bioconductor_full:devel' } }
    stages {
        stage('build') {
            steps {
                bash -e R -e "date()"
            }
        }
    }
}
