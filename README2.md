# `action steps` - UPDATED README

This repo demonstrates several ways of using Github commit messages to trigger performative actions using Github Actions. THink of it as using commit messages as a command line interface.

Current examples include:

- As your commit message, enter: `Update Readme` to replace this README file with an updated one (`README2.md in the *READMEs* branch.  Enter `Reset Readme` to replace this readme with the original.
- If you upload one or more zip files as part of a commit, and start the commit message with `Unzip`, the zipped files will be unzipped and committed to the repo, and the zip file will be deleted (i.e. removed from the repo).
