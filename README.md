[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8588215&assignment_repo_type=AssignmentRepo)
| EAPS 591 - Numerical Modeling of Planetary Orbits | Fall 2022 | [YOUR NAME] |
| ----------------------------- | --------- | ------------------ |

# Module 5 - Symplectic Integrators - Code infrastructure
## Problem 4. Cartesian coordinates to orbital elements

### Instructions for using the coordinate conversion code

1) manually run the first cell
2) TO RUN THE SECOND CELL:
- filename: update this based on the csv you want to read. You should only need to change the last two digits before the hyphen.
- source_paths: specify where you want to save this. The default is where I saved it, but the last subdirectory (i.e., /filename.csv') should remain unchanged. This part will get updated in the next few lines automatically based on the planet of interest. 
- target_paths: all you have to update here is the '/id0000XX-XV.csv'. 
- same applies for the subsequent source and target paths

3) After you've specified the planet of interest/file paths in the second cell, go to cell > run all below. 
4) The code is set up such that it will only save/update a specific planet's plot/dataframe when that is the filepath specified. 
5) this worked on my computer, I had to spent some time making it easily adaptable for others (when I realized I'd specified extremely specific filepaths). I would've just done it in Spyder, but I forgot you (Dave Minton) were going to have to be able to run it too. 

