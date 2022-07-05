node{
    stage( 'clone javacode'){
        git 'https://github.com/suniani/mahalogin.git'
    }
    stage('execute mymaven on targets'){
       sh 'mvn install' 
    }
    
}
