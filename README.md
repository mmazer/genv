### genv

A simple Grails version manager.

It was written to manage Grails versions on Windows using the [Git for Windows](https://msysgit.github.io/) bash shell.

While [GVM](http://gvmtool.net/) offers much more functionality there were some compatibility issues using it under `msysgit`. 

There is also [Gravy](https://github.com/enterprise-grails/gravy) for using Grails with the Windows command shell.

#### Installation

1 Clone the `genv` repository into your home directory, e.g. :

        git clone https://github.com/mmazer/genv.git .genv

2. Add the `.genv/bin`  directory to your PATH.

3. Install any versions of Grails under `.genv/grails` using the version number as the sub-directory name.

4. You can specify default arguments for running Grails by creating a `grails.ini` file in the `genv` directory, e.g. :

        --plain-output

#### Usage

1. Run `genv -h` to see available options.

2. Once a default version has been set, run `grails` to launch it.

