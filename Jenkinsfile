node{
    stage( 'clone javacode'){
        git 'https://github.com/suniani/mahalogin.git'
    }
    stage('execute maven on target'){
       sh 'mvn install' 
    }
    
}
