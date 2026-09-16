@Library('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]

if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    nodejsEKSpipeline(configMap)
}
else {
    // nodejsEKSMain(configMap) 
    nodejsEKSPipeline(configMap)
}