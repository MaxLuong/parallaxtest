cd ~/website

== Initial setup ==
git init

== Commit ==
git commit -a

==Update==
git pull https://github.com/MaxLuong/parallaxtest master

==Commit==
git remote add origin https://github.com/MaxLuong/parallaxtest
git push origin master

==Deploy==
gcloud app deploy app.yaml


== Git from Codenvy ==
Occasionally have to go to Profile -> Preferences -> VCS -> SSH
and hit the cat icon

==Github==
parallaxtest

gh auth login
