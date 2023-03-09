Console.WriteLine("hello world");


https://github.com/mishna8/TEST.git

CREATE A NEW REPOSITORY
echo "# TEST" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mishna8/TEST.git
git push -u origin main


OR PUSH AN EXISTING REPOSITORY 
git remote add origin https://github.com/mishna8/TEST.git
git branch -M main
git push -u origin main