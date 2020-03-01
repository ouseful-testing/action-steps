# `action steps` - ORIGINAL README

This repo demonstrates several ways of using Github commit messages to trigger performative actions using Github Actions. Think of it as using commit messages as a command line interface.

Current examples include:

- As your commit message, enter: `Update Readme` to replace this README file with an updated one (`README2.md` in the *master* branch.  Enter `Reset Readme` to replace this readme with the original.
- If you upload one or more zip files as part of a commit, and start the commit message with `Unzip`, the zipped files will be unzipped and committed to the repo, and the zip file will be deleted (i.e. removed from the repo).
- Create a dummy file or edit `commands.txt` to give you a chance to enter a commit message. Using a message of the form `Fetch URL OUTDIR`, where `URL` is URL from an OpenLearn Unit (such as https://www.open.edu/openlearn/science-maths-technology/chemistry/the-molecular-world/content-section-1.1) and `OUTDIR` is the directory you want the content to be place in (for example, `demo2`) to give a commit message of the form:  `Fetch https://www.open.edu/openlearn/science-maths-technology/chemistry/the-molecular-world/content-section-1.1 demoN`. This will download the OU-XML source of an OpenLearn unit along with any associated image files and generate a markdown version of the unit into `./demoN`. NOTE: it's probably best not to try to save the content into a directory that currently exists. By the by, you'll also get the XML and images saved into a SQLite3 database: `openlearn_oer.db`.
