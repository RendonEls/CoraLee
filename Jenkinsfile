// see https://dzone.com/refcardz/continuous-delivery-with-jenkins-workflow for tutorial
// see https://documentation.cloudbees.com/docs/cookbook/_pipeline_dsl_keywords.html for dsl reference
// This Jenkinsfile should simulate a minimal Jenkins pipeline and can serve as a starting point.
// NOTE: sleep commands are solelely inserted for the purpose of simulating long running tasks when you run the pipeline
node {
    // Mark the code checkout 'stage'....
    stage 'checkout'

    // Get some code from a GitHub repository
    git url: 'https://github.com/RendonEls/CoraLee.git'
    sh 'git clean -fdx; sleep 4;'

}
