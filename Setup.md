# Git Reminder

Hello this is the note for git.
Feel free to add extra git commands here

# SSH
<h4>Create new key</h4>

~~~shell script
ssh-keygen
~~~

<h6>Press Enter for everything</h6>

<h4>Read Public Key</h4>

~~~
cd ~/.ssh/
cat id_rsa.pub
~~~

# Add SSH key on GIT
<h6>In the upper-right corner of any page, click your profile photo, then click Settings.</h6>
<img src="imgs/userbar-account-settings.png">
<h6>In the user settings sidebar, click SSH and GPG keys.</h6>
<img src="imgs/settings-sidebar-ssh-keys.png">
<h6>Click New SSH key or Add SSH key.</h6>
<img src="imgs/ssh-add-ssh-key.png">
<h6>In the "Title" field, add a descriptive label for the new key. For example, if you're using a personal Mac, you might call this key "Personal MacBook Air".</h6>
<h6>Paste your key into the "Key" field.</h6>
<img src="imgs/ssh-key-paste.png">
<h6>Click Add SSH key.</h6>
<img src="imgs/ssh-add-key.png">
<br>
[Git Docs on Add a new SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)