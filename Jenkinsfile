node {
   stage("check parameters"){
       echo this.class.toString()
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
   stage("Running Tests"){
       echo "checkout"
   }
}
