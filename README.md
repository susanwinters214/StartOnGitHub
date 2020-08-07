# StartOnGitHub
Creating a GitHub Project (aka "Repo")

#Have a website on your COMPUTER and you want to upload it to GitHub?

1. Go to GitHub, log in and click the button to start a new "repo".
2. On the next page you'll see a long URL for your gitHub project. 
3. Copy that to your clipboard

On your computer, navigate to your project in the Terminal (via VS Code)
1. git init
2. git add .
3. git commit -m (My New Project's Name)
4. git remote add origin PasteYourLongURLhere.git  
5. git remote -v
(This will confirm that this is a working URL and will repeat it back to you - hit enter to continue)
6. git push origin master

That's it. You're done!
You can now go back over to GitHub.com and see that your files have been uploaded to the new repo.
    
