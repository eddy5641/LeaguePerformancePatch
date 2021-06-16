# LeaguePerformancePatch
The league client is noctorious for bugs and performance issues. This tool patches out bugs, and enhances performance

Note: This is a tool that is use at your own risk. I wouldn't say that this gives you any advantage over other players, unless you consider a faster client an unfair advantage. An example is when I play normals on OCE (180 ping), I am basically able to call the roll I want because my client tends to be just a lil less chonktastic

# Patches
- [ ] LChormiumFix - A patch to Chromium to fix memory leak issues specific to the LCU
- [ ] PerformancePatch - A micro-patch that updates the garbage collector to be more LCU specific
- [ ] AnimationReduce - A patch that allows for users to reduce the amount of animations to increase performance
- [ ] SysSocket (Beta) - A large patch that removes the Client Client API and moves everything over to Named Pipes. This uses one of my libraries called SockPipes. This is a beta feature as it greatly increases performance, but has massive modifications to the communication betwean LeagueClient and LeagueClientUx. This is an unstable patch.
- [ ] LazyAgroPlugins - A patch that forces some plugins to be lazy loaded and some to be cached. Some of these plugins have been modified to allow for reuse.
- [ ] NativePluginLoader - A patch that optimizes plugins for TurboFan

# Real world comparison

## Without

![Without A](https://eddy.img.jannasharp.gg/8X8EYBebI7.png)

![Without B](https://eddy.img.jannasharp.gg/XP8PNO96CL.png)

## With

TBA
