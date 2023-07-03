cd ~/website

== Initial setup ==
git init
git pull https://github.com/MaxLuong/parallaxtest master

== Commit ==
git add *

==Update==
git pull

==Commit==
git commit -a
git push origin master

==Deploy==
gcloud app deploy app.yaml


== Git from Codenvy ==
Occasionally have to go to Profile -> Preferences -> VCS -> SSH
and hit the cat icon

==Github==
parallaxtest

gh auth login
