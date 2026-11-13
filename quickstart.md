# What is Git?

Git is a version control system, a tool used to record and manage changes to files over time, especially in software development.

# Quickstart (hands-on)
 
1. Create a folder
````bash
mkdir git-practice
````

2. Navigate into the folder
````bash
cd git-practice
````

3. Initialize a git repository
````bash
git init
````

4. Create a file
````bash
echo "Hello, Git" > my-first-file.txt
````

5. Add the file to the staging area
````bash
git add my-first-file.txt
````
or use 
````bash
git add .
````
to add all files in the folder.

6. Commit the changes
````bash
git commit -m "first commit"
````
---
7. (Optional) Push to repository
````bash
git push -u origin main
````