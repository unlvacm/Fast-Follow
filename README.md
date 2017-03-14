## Synopsis

This an installation Guide for Windows x64 machines. We do not own React-Native or Android Studio.

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

This Guide exists for the sole purpose of UNLV ACM or UNLV ACM members who are involved in the open Source
project.

## Installation

Before Installing React-Native make sure you have the latest java JDK installed. This dependency
can be checked by using you command terminal in Windows.

```
java -version
```
If you don't have java installed in your Windows machine follow this link for installing the lastest
java JDK. http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

Run the java installation exe and let it install into the default path.

Make sure you specify the path for java in your machine. This can be easily done by going to your
environment variables and adding a new path JAVA_HOME.

![Image 1](https://github.com/unlvacm/Fast-Follow/README_images/Win_Pics/env_var1.jpg)
PICTURE env_var1.jpg

PICTUE env_var2.jpg

** MAKE sure you set up your JAVA_HOME variable value correctly in your environment variables.

After installing Java we need to install chocolatey so it can install node.js and python2.7.
Just go to this link scroll down and click on more options under the More Install Options header
to view more. Scroll down and copy the cmd.exe command.

Looks something like this:

PICTURE choco_cmd.jpg

Copy that cmd.exe command and paste it into the command line terminal. Just type 'y' to agree to the
installation.

Verify your chocolatey installation by typing in
```
choco
```
into the command line.

Now, let's install Python2.7 and node.js

To install Python2.7 run the following command in to command line terminal
```
choco install python2
```

Verify you have python2.7 by typing in
```
python --version
```

Next install node.js by running the following command
```
choco install nodejs.install
```

Verify node.js by typing in
```
node --version
```

Now for the most important part of React-Native installing Android Studio:

Go to this link https://developer.android.com/studio/index.html and download Android Studio


## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
