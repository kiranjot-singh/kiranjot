node {
    stage('Checkout') {
        dir('saas-ui') {
            checkout scm
            scmUrl = scm.getUserRemoteConfigs()
            echo scmUrl
        }
    }

}
