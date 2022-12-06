# installer

This is the manual for the Installation and deployment process
It contains not much as not much is needed

If your a Linux user you should install nodejs to have a good base system for your cloud migration.

If your a MacOS user you use our command line installer or when your a nodejs developer maybe follow the above methods for linux

If your a Windows user you should use our command line based installer.

If your a Android Developer install the GraalVM Stack and graaljs then use graal node to spin up .... to be done es4x tutorial.

If your a Embedded Device Developer eg windriver use the Linux setup and simply choose the correct target configurations in the build tools. Also it would be help full at this point if you could at last code wasm or c++ or rust without macros

## The 2 Types of InterOp

- API using what the existing platform or device gives us in case of 
  - linux that is the stdio,dbus,fs interfaces. 
  - windows that is the shell and windows apis
  - macos the mac apis
  - android the andoird apis 
  - browser the browser web apis w3c legacy web
- Nativ using what ever we can to interact with it in its nativ way eg: asm run watch. most time libc in reality.


