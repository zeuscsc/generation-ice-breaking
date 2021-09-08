# Clone
<h6>Copy the link from git</h6>
<img src="/imgs/git-clone.png">

~~~shell
git clone git@github.com:zeuscsc/generation-ice-breaking.git
cd generation-ice-breaking
~~~

# Push
~~~shell
git add .
git commit -m "What have I done~!"
git push
~~~

# Pull
~~~
git pull
~~~

# Merge
Remember something you need to merge
Accept Current means using your own version over your friends
Accept Incomming means using your friends version over yours
Accept Both mean add both code you the file
After merge, 
~~~shell
git add .
git commit -m "merge"
git pull
git push
~~~
Something you may found <<<< inside the files, remove them carefully or git will think your files need to merge everytime.