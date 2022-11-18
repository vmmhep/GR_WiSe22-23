# Introduction to General Relativity -- Winter Semester 2022/23

**JuPyTer notebooks for General Relativity course delivered at Uni-Goe and BZU.**

Assuming you are on a `UNIX` based operating system, you can simply copy the following command into a terminal window:
```bash
mkdir $HOME/GR22 && cd $HOME/GR22 && git pull https://github.com/vmmhep/GR_WiSe22-23.git
```
which will make a directory in your `HOME` directory called `GR22` and then copy this git repository there.[^0]
[^0]: Unfortunately, I don't have access to a Windows machine and so am not able to provide guidance.  However, some online searching should bring you all the steps you need.

If you don't have a `jupyter` instance installed on your computer, we suggest using a `docker` container.  You can install `docker` by following the instructions on [this webpage](https://docs.docker.com/get-docker/).[^1]

[^1]: An alternative method would be to use your favourite IDE (I like VSCode) and install the relevant add-on

Once there, you can look for a `docker` container that gives you a `jupyter` instance, _e.g._ [this one](https://hub.docker.com/r/mikebirdgeneau/jupyterlab).

After that, load up `jupyter` and navigate to the `GR22` directory and bring up the specific notebook.  Most sheets will only be `markdown`, however, as the course advances, some numerics will be included and will therefore require `jupyter` to have a `python` or `julia` kernel running.

Enjoy the course!