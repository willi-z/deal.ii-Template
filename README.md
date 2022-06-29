# deal.ii-Template
> Project Template for good deal.ii-Project

## Setup

- what kind of operation system do you use:
  - Windows: 
    - Please install wsl! Running deal.ii under Windows is a bet not worth taking!
    - Read [Using deal.II with the Windows Subsystem for Linux](https://github.com/dealii/dealii/wiki/Windows#using-dealii-with-the-windows-subsystem-for-linux)
    - [Visual Studio and WSL 2](https://docs.microsoft.com/en-us/cpp/build/walkthrough-build-debug-wsl2?view=msvc-170)
  - Mac: 
    - see [MacOSX](https://github.com/dealii/dealii/wiki/MacOSX) and [Apple ARM M1 OSX](https://github.com/dealii/dealii/wiki/Apple-ARM-M1-OSX)
  - Linux: everthing is fine! Please contiue! 
- clone the repository 
  ````bash
  git clone
  ````
  
### Change the deal.ii-version

```
 export REPO=ppa:ginggs/deal.ii-9.3.2-backports # old version
 add-apt-repository --remove $REPO
```

```
 export REPO=ppa:ginggs/deal.ii-9.4.0-backports # new version
 add-apt-repository $REPO
 apt-get update
 apt-get install libdeal.ii-dev libdeal.ii-doc # could not test this
```

### Deployment

In case the project has to deployed some where, several options exist:
- create a dockerimage
- compile your code to an excecutable


## Sources

- [deal.ii tutorial series](https://www.dealii.org/current/doxygen/deal.II/Tutorial.html)

### Videos

- [scientific computing with deal.ii](https://www.math.colostate.edu/~bangerth/videos.html)
- [working with deal.ii](https://www.youtube.com/playlist?list=PLS1lqxOwNjOZ-Zo8oHvh9-xvrudP7mYRp)
