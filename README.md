# SLF4J

A logging abstraction layer, NOT an implementation.
It is meant to allow other developers to use their own desired logging implementation, and prevent project from depending on multiple logging APIs.

Examples of these logging implementations are log4j or the Java Loggin Util (JLU) API.

[SLF4J User Manual](https://www.slf4j.org/manual.html)

## Usage
In the project's root directory add the submodule

Format: `git submodule add [git clone URL] [destination directory]`

$ `git submodule add https://github.com/FIUDiscoveryLab/SLF4J.git ThirdParty/SFL4J/`
