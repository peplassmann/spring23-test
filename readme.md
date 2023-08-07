# Exercise 02

The goal of this exercise is to use GitHub to clone a repository, fix a simple bug, and then push/commit the solution to GitHub.

1. Create a working directory somewhere on your computer. Open your command line terminal and make a working directory. Then change to that directory.

2. Clone the assignment for today. Accept the GitHub classroom invitation. This will automatically add this repository accessible to you and the instructor/TAs with some starter files. You can then clone it to your computer using

	```git clone https://github.com/VT-ECE-3514/spring23-ex02-USER.git```
	
	where USER is your GitHub username. You may have to enter your GitHub 
	username and password.
	
3. Configure your build directory using CMake and build the tests. Run the tests from inside your IDE (assuming you use one) and/or from the command line.

4. In the file ``rational.cpp`` there is a silly bug (you can see it by running the unit tests). Correct the bug.
	
5. Add the updates to your repository and commit the changes, e.g.

	```
	git add -u
   	git commit -m "fixed bug in rational.cpp"
	```
	
6. Use git push to synchronize the repository with that on GitHub

	```git push```
	
	You may have to enter your GitHub username and password again.

You have now completed the exercise.
