git clone https://github.com/Kandharikunal/SSD-Lab-Activity-2.git
mkdir Lab Activity 2
cd Lab Activity 2
touch README.md
git add README.md
git commit -m "Add readme.md"

touch hello_world.txt
git add hello_world.txt
git commit -m "Add hello_world.txt"

git push origin master
git checkout-b New Branch
touch test.txt
git add test.txt
git push-set upstream origin New Branch
git branch -d  New Branch
