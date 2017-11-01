# forge-tools

Tools for going through the data from the Puppet forge

The tools all operate on data in the `data` directory in this checkout.

Change your `PATH` to include the `bin` directory from this repo.

To get started, run `latest`. This will create a directory `data/tarballs`
containing the latest version of each Forge tarball. Then run `unpack`
which will unpack them in `data/code`. Finally, run `link` which will
create additional directories like `provider` and `type` linking to
subdirectories of individual modules that contain such data.
