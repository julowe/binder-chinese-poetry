Example on how to use post-build scripts to install latex requirements of
matplotlib

For more information on post-build scripts, please refer to

http://repo2docker.readthedocs.io/en/latest/samples.html#system-post-build-scripts

The postBuild file creates and deletes one figure with matplotlib to generate
the font cache (and speed up subsequent runs).
