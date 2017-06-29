Homebrew installer for Mac OS X

To test locally, first create the installer:

```bash
brew create <URL of tarball>
```

This command will create a Ruby file and open it in your favorite editor.

Edit the generated Ruby file, replace the contents with the contents of
hyperledger-fabric-1.0.0.rb which is in this directory, and save the file.

Then, test the installer:

```bash
brew install hyperledger-fabric
```

Then, check to see whether the binaries have been properly installed:

```bash
which cryptogen
which configtxgen
```

Note: we will need to agree on a location from which to retrieve the tarball
that should be named hyperledger-fabric-1.0.0.tar.gz

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
