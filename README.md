# MIT18065



## Installation
* Summary:  We will download Julia, start it in a terminal, download a ton of (free!) software, and then open up a Jupyter Notebook.
(A better installation, especially for Windows, will be available Monday.)

* Install Julia 0.5 (command line version) as described in http://julialang.org/downloads/
* Pick one entry from the table (`.exe` for Windows, `.dmg` for Mac, binaries for Linux) and download
* Install the program
* Start up Julia. (Your first Julia will be in a command/terminal window.)
* (There should be an icon or a launch button with the three-colored Julia logo <image src=https://avatars0.githubusercontent.com/u/743164?v=3&s=30>)
* Type `1+1`, just for fun.  You know what we're hoping to see...
* Type `Pkg.init()`. [This initialises the directory where Julia packages are stored.]
* Ignore pink ugly info or warning messages; they are not serious. 
* We found that on a Mac it ran right away, but on Windows it took a couple of minutes. Good time
  to get that coffee or Diet Coke.
* Run `Pkg.clone("https://github.com/SimonDanisch/MIT18065.git")`. 
This took about 30 minutes on windows, and about 7 on my Mac. 
For Windows users, good time to get dinner. (Your time may vary.)
* Run `Pkg.test("MIT18065")` to make sure that everything is correctly installed.
It will open a web browser where you can select `getting started.ipynb`, which will lead you to this:
[notebook](https://github.com/SimonDanisch/MIT18065/blob/master/docs/getting%20started.ipynb)
