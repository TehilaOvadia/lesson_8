properties([[$class: 'JiraProjectProperty'], parameters([string(defaultValue: 'Tehila', description: '', name: 'NAME', trim: false)]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/TehilaOvadia/lesson_8.git"
    }
    stage("show"){
        sh "ls"
    }
}
