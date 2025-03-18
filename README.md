# 3094

## Ideas for how to get the project working:
- Make it so the user copies the input file into the program directory
- Have a function that takes the file as input? Something that scans the local directory? Or make sure the input files have a specific name (make them all "input"?) **NEED TO WORK OUT THE LOGISTICS**
- Have files that are for each of the test suites?
- Functions that are commonly called test combinations for each test. Each test has its own file **FOCUS ON MODULAR FUNCTIONS**
- Then, have a "main.py", to tie everything all together and act as a main menu.

## Ideal Runtime Scenatrio:
- User has input file in the directory
- Runs the program.
- Selects the test on the input
- Test is called
- Output of the tests are displayed in a markdown file, for the user to do whatever with.


## Logistics
I am not sure about the logistics
- User needs to have the input files they want 
- Could have it so the user drags/drops the input file into the terminal? (IDK if this is achievable)

## Running Thoughts:
- Have "-v"/verbose option as standard. -> Seems like the most warranted option.
- Need to ensure modularity (for ease of future developmemt)
- How to get the input file to work? Is it even doable? **ASK CARLTON** I feel like it will be doable, but maybe not in the way I expect
- 

## Using terminal GIT:
1. git add <FILE>
2. git commit -m "<MESSAGE>"
3. git push