pipeline{
agent any
stages{
stages('Checkout Code'){
steps{
git 'https://github.com/your-repo/sample-project.git'
}
}
stag('Build'){
steps{
sh 'javac Main.java' //Example build step for java
}
}
stage('Test'){
steps{
sh 'java Main' 
}
}
stage('Deploy'){
steps{
echo 'Deploying application...'
}
}
}
}
