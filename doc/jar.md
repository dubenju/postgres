assoc .jar=CompressedFolder
assoc .gz=CompressedFolder
Can you configure Windows to open JAR files like ZIP files without a 3rd party tool?
I'd like to be able to examine the contents of a JAR file without having to install Winzip or some other tool and without having to rename the file. Windows Explorer can open ZIP files just fine; is there some registry setting I can use to let it treat JARs like ZIPs?

Or from the command line:

assoc .jar=CompressedFolder
Under Vista (or higher) you have to run this in an elevated Command Prompt.
