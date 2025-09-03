




# C++ Programming Lab 1: Outputting to the Console Window


---

## Setting up 

- Right now you should be reading this project in my GitHub page.

- What you will do, is download the this project as a zip.

- Click on the green button and the at bottom there should be download zip. Click it!

![alt text](images/image.png)

- Once you have done that, go to downloads right click and extract the folder

![alt text](images/image2.png)

- It is similar process for Macs!



- Once that is done, just like the previous Lab, you will open Visual Studio Code
- Once you are in VS Code, you will open click open folder, and open Lab1 folder. 
- If the following window comes up, you should click the the option that I have bordered in black.

![alt text](images/image13.png)

- After doing that you should you should see the following in your window.

![alt text](images/image3.png)

- Once you have done that you should see the following

![alt text](images/image4.png)
---
## Compile and Run Your Program.

- Just like in the previous Lab0, open up the Developer Command Prompt if you are using Windows or desktop computers. If you are using mac then open up the terminal program.

- In the terminal window run the following.

```bash
cd /
cd [path_to_lab1_folder]
mkdir build
cd build
cmake ..
```

---
### Window/Desktop Users
- Next you will do the following everytime you make changes to your program and you need to rerun your program. Mac users jump to next section. You will do the same except a different way. This is the most important part of the lab!

```bash
msbuild ALL_BUILD.vcxproj
cd /Debug
./lab1.exe
cd ..
```
---
### MAC users

Make sure you are in the build directory in the terminal

```bash
cd build
```
- Now everytime you need to run your code do the following.
```bash 
make
./lab1
```
---
## Starting Lab 1

- Go the to src folder and open exercises.cpp file.
- You should see 3 TODOs

![alt text](images/image5.png)

- Everytime you want to run your program after you make changes,
Go back to the section that I mentioned above that needs to be repeated everytime you run your program.


## Turning in your Assignment

- You will compress your folder Lab1 to a zip file
- You will then submit the zip file to canvas.