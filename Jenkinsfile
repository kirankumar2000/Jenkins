// pipeline {
//     agent any 
//     stages {
//         stage('Bulid') {
//             steps {
//                 echo 'Built'
//             }
//         }
//          stage('Test') {
//             steps {
//                 echo 'Tested !' 
//             }
//         }
//         stage('Deploy') {
//             steps {
//                 echo 'Successfully Deployed !' 
//             }
//         }
        
//     }
//     post{
//         always{
//             echo 'Success or Failure'
//         }
//         success{
//             echo 'Success'
//         }
//         failure{
//                 echo 'Failure'
//             }
//         }
    
// }

// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
    // This displays colors using the 'xterm' ansi color map.
    ansiColor('xterm') {
        // Just some echoes to show the ANSI color.
        stage ("\u001B[31mI'm Red\u001B[0m Now not")
    }
}
