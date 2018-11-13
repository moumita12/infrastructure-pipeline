properties([pipelineTriggers([githubPush()])])

node('linux') {
    git url: 'https://github.com/moumita12/infrastructure-pipeline.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}
