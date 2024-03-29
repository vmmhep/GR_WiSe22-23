# Introduction to General Relativity -- Winter Semester 2022/23

**JuPytR notebooks for General Relativity course delivered at Uni-Goe and BZU.**

Assuming you are on a `UNIX` based operating system, you can simply copy the following command into a terminal window:
```bash
mkdir $HOME/GR22 && cd $HOME/GR22 && git init && git pull https://github.com/vmmhep/GR_WiSe22-23.git
```
which will make a directory in your `HOME` directory called `GR22` and then copy this git repository there.[^0][^1]
[^0]: Unfortunately, I don't have access to a Windows machine and so am not able to provide guidance.  However, some online searching should bring you all the steps you need.

[^1]: After initially `pull`ing the repository, you will only need to 
    ```bash
    cd $HOME/GR22 && git pull https://github.com/vmmhep/GR_WiSe22-23.git
    ``` 
    to get updates.

If you don't have a `jupyter` instance installed on your computer, we suggest using a `docker` container.  You can install `docker` by following the instructions on [this webpage](https://docs.docker.com/get-docker/).[^2]

[^2]: An alternative method would be to use your favourite IDE (I like VSCode) and install the relevant add-on

Once there, you can look for a `docker` container that gives you a `jupyter` instance, _e.g._ [this one](https://hub.docker.com/r/mikebirdgeneau/jupyterlab).

After that, load up `jupyter` and navigate to the `GR22` directory and bring up the specific notebook.  Most sheets will only be `markdown`, however, as the course advances, some numerics will be included and will therefore require `jupyter` to have a `python` or `julia` kernel running.

You can also run the notebooks in the cloud using the `binder` links provided:<br>
Click here to load exercises 1 <br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vmmhep/GR_WiSe22-23/main?labpath=exercises1.ipynb)

Click here to load exercises 2 <br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vmmhep/GR_WiSe22-23/main?labpath=exercises2.ipynb)

Click here to load exercises 3 <br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vmmhep/GR_WiSe22-23/main?labpath=exercises3.ipynb)

Click here to load exercises 4 <br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vmmhep/GR_WiSe22-23/main?labpath=exercises4.ipynb)

Enjoy the course!
