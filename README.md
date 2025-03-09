# Small-Feline-Big-deadline
CSC8503 - Advanced Game Technologies - C++/OpenGL
This game was created in C++ using OpenGL rendering and a basic codebase provided by Newcastle University. During the development of this game, I created most of the physics simulations and AI behavior shown in-game. 
This ranged from programming impulse calculations and handling multiple collision types, to creating finite state machines and pushdown automata. 
This project focused entirely on gameplay programming, and not graphical features, clearly.


### Install:
Install instructions for compiling and running project using CMake (Instructions provided by Rich Davison, Lecturer in Game Engineering, Newcastle University)
- Install CMake (if you can), or extract the zip to a folder somewhere - the exe will be in the /bin/ subfolder.
- Extract the CSC8503 zip somewhere on your C: drive.
- Open up CMake, and set the 'Where is the source code' and 'Where to build the binaries' folder to the folder you extracted the code to.
- Go to File, and then select Delete Cache.
- Press the Configure button in the bottom left of CMake. Leave the dialog box options alone and press Finish.
- Press Generate. If you want to take a look at a different rendering API, select the USE_VULKAN tickbox, and then press Generate.
- Press Open Project.
- You should then be able to compile your VS solution as normal.
