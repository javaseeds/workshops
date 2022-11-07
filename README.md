<img src="https://www.graalvm.org/resources/img/home/logo_mobile_openmenu.svg" 
    alt="GraalVM logo" 
    width="200px">

# GraalVM Labs and Tutorials

This repository contains several labs and tutorials
that will guide you through getting started with and using GraalVM. It also provides labs that deep-dive into particular 
topics, such as how reflection and Class loading works within GraalVM Native Image.

This repository is continually updated with new labs and tutorials added frequently. Please check in regularly
to keep up to date.

To find out more about GraalVM, take a look at our website: [GraalVM](https://www.graalvm.org).

## Using the Labs and Tutorials

All of the labs are written so that they will work on your own device (laptop, server). Each lab begins with
prerequisites that you need to have installed. Please make sure you read these.

First, clone this repository:

```bash
git clone https://github.com/graalvm/workshops.git
```

Open a terminal, change directory to the lab / tutorial you want to try out. Read the `README.md` file.
The labs are organized into directories as follows:

* `native-image` : This collects all labs related to GraalVM Native Image

We will add more directories as we add more content including ones relating to `native-image`, `polyglot` and using
GraalVM as a Java runtime.

## Native Image Labs and Tutorials

### First Steps

Begin with these labs and tutorials if you want to learn about GraalVM Native Image:

1. [GraalVM Native Image Quick Start](native-image/graalvm-native-image-quick-start/) &nbsp; <a href="https://github.com/graalvm/workshops/actions/workflows/github-actions-native-image-quickstart.yml">
<img alt="native-image-quickstart" src="https://github.com/graalvm/workshops/actions/workflows/github-actions-native-image-quickstart.yml/badge.svg" /></a>

>  Workshop to gently introduce you to working with GraalVM Native Image. In the workshop you will:
>  - Build and run a Java application, using GraalVM
>  - Turn a Java application into a native executable, using GraalVM Native Image
>  - Build a native executable that works with the dynamic features of Java
>  - Use the Maven GraalVM plugin to build a native executable using GraalVM Native Image2.

2. [Understanding Reflection with GraalVM Native Image](native-image/reflection/) &nbsp; <a href="https://github.com/graalvm/workshops/actions/workflows/github-actions-native-image-reflection.yml">
   <img alt="native-image-quickstart" src="https://github.com/graalvm/workshops/actions/workflows/github-actions-native-image-reflection.yml/badge.svg" /></a>

>  Workshop that will help you understand how reflection works within GraalVM Native Image. In the workshop you will: 
>  - Use the `native-image` tool to compile a Java application that uses reflection into a native executable file
>  - Learn about the assisted configuration tooling provided by GraalVM

3. [GraalVM Native Image Build Tools, for Maven](native-image/native-build-tools/)

>  Workshop where you will:
>  - Learn about the _GraalVM Native Image Build Tools for Maven_

### Next Steps

With a good grounding in the basics of GraalVM Native Image, try out these:

1. [GraalVM Native Image, Spring & Containers](native-image/containerisation/) &nbsp; <a href="https://github.com/graalvm/workshops/actions/workflows/github-actions-native-image-containerisation.yml">
   <img alt="native-image-quickstart" src="https://github.com/graalvm/workshops/actions/workflows/github-actions-native-image-containerisation.yml/badge.svg" /></a>

>  Workshop introducing using GraalVM Native Image in containers. In this workshop you will:
>  - Add a basic Spring Boot application to a Docker Image and run it
>  - Build a native executable from this application, using GraalVM Native Image
>  - Add the native executable to a Docker Image
>  - Shrink your application docker image size with GraalVM Native Image and Distroless containers 

2. [Non-Fungible Verses](native-image/non-fungible-verses/)

>  Workshop that builds upon the containerisation workshop. It adds:  
> 
>  - An introduction to some of the capabilities of the Oracle Cloud Infrastructure (OCI) always free tier.
>  - Showw how using [GraalVM Native Image](https://docs.oracle.com/en/graalvm/enterprise/22/docs/reference-manual/native-image/) can help you make the most of your free tier allocation


