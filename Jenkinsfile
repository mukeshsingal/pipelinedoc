node {
   stage("Check provided parameters"){
       echo "checkout"
   }
   parallel(
      Android: {
       echo "This is branch a"
      },
      Ios: {
       echo "This is branch b"
      },
      Spa: {
       echo "This is branch b"
      }
    )
    
}
