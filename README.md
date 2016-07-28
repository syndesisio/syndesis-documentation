Documentation for iPaaS - a platform for running JBoss Fuse on the enterprise public cloud (OpenShift Dedicated).

### FAQ

*Q. I'm new to Asciidoc. How do I get this stuff to work?*

Just follow these steps:

1.  Install Asciidoctor. On Fedora, this is as easy as:

        $ sudo yum install asciidoctor
    For other platforms, see [Installing the Toolchain](http://asciidoctor.org/docs/install-toolchain/).
2.  Build a book using `asciidoctor`. For example:

        $ cd ipaas_user
        $ asciidoctor master.adoc