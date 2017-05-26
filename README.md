# kotlin-skel
This is a skeleton project for programming FRC robots in Kotlin.
## Usage
### Setting the main class
You will need to change the `MainClass` setting in `build.gradle` to reflect your project. In your main class file, you will need to add `@file:JvmName("Robot")` or somethig similar so that the JVM can find it.
### Building
`./gradlew build`
### Deploying
`./gradlew deploy`

If you get an rsync error, you may need to run `./installRioRsync.py`.