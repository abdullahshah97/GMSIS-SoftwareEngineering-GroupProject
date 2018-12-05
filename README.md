# GM-SIS

![GM-SIS graphic](GM-SIS/src/gmsis/ui/gmsis-splash.png)

This version of GM-SIS was produced by Team 10 for the ECS506U.

## Requirements

To run GM-SIS, you will need Java 8, minimum version 1.8u60 (higher on Windows) with either Oracle JavaFX Runtime or OpenJFX Runtime.
A copy of Oracle's JRE 1.8u121 is provided in the release .tar.xz file for both Windows and Linux.

## Running GM-SIS

The following commands assume you are in the directory containing `gmsis.jar`.

To run GM-SIS with your system Java, use the following command:

```bash
java -jar gmsis.jar
```

To run GM-SIS with the bundled JRE on Linux, use the following command:

```bash
./launch-gmsis.sh
# Equivalent to below but also updates JAVA_HOME and PATH for that run
# ./jre1.8.0_121-linux/bin/java -jar gmsis.jar
```

To run GM-SIS with the bundled JRE on Windows, use the following command:

```bash
./jre1.8.0_121-windows/bin/java.exe -jar gmsis.jar
```
