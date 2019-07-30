// Jenkinsfile
//@Library('evenOdd') _

evenOdd(currentBuild.getNumber())
echo 'Loading wolox-ci library'
node {
  woloxCi('./test.yml')
}
