pipeline
{
agent any
stages
{
stage('clone')
{
steps
{
git 'https://github.com/Kavya-123S/demo2_rep.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
