# groovy-native 

Gradle skeleton to compile natively a Groovy app 
with Graal native compiler inspired by [GraalVM with Groovy and Grape - creating native image of a standalone script](https://e.printstacktrace.blog/2019/01/graalvm-groovy-grape-creating-native-image-of-standalone-script/).

## Quick start 

Compile the application with the command: 

    ./gradlew nativeImage

Run it with the command:

    ./build/graal/hello-graal 
    

### Links
- https://github.com/palantir/gradle-graal
- https://medium.com/palantir/first-steps-with-graal-and-substrate-vm-193f8a8bf60e

