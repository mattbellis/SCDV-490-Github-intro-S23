# SCDV-490-Github-intro-S23
An introduction to Github for Siena's SCDV 490: Group Projects in Data Science course

*This exercise should be done in guidance with the instructor*

## First activity

### Clone the repo
From your git command line, 

```
git clone https://github.com/mattbellis/SCDV-490-Github-intro-S23.git
```

### Make some edits

Fire up a jupyter-notebook environment in this new `SCDV-490-Github-intro-S23` directory. 

Open up `test_demo_tools_A.ipynb` and go through the exercise. Make sure you read everything carefully.

### Push your changes...psyche!

Just kidding...you can't push your changes because

* You are not the owner of this repository
* You are not a *collaborator*
* You did not fork the repository

Let's try this again, but we will *fork* the repository.

## Second activity

### Fork the repo

Fork this repository, following the more general instructions given here

https://docs.github.com/en/get-started/quickstart/fork-a-repo

*Make sure you sync the fork with the upstream repository*

### Make some edits

Edit the `names.py` file and fix yours (*and only yours!*) information.

### Push the changes

Commit and push your changes

```
git commit -m "YOUR COMMIT MESSAGE HERE" name.py
git push
```

Make a `pull` request for me (the original author) by following the instructions here

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork

### Get the changes

Fetch the upstream changes (once the instructor has approved all the pull requests) by following the information here for the *command line*

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork

## Third activity

Create a new text file from the jupyter dashboard. Name it ```YOURLASTNAME.txt``` and put some text in it about how you think the class is going (*remember...this text will be visible to your peers and the world!).

Add this file to the repo, otherwise it won't get pushed to github. Then commit your changes and push. 

```
git add YOURLASTNAME.txt
git commit -m "YOUR COMMIT MESSAGE HERE" YOURLASTNAME.txt
git push
```

Make a pull request for your new file

## Fourth activity

Break up into pairs. Each of you should

* Create a new repo
* Add a couple of files in there
* Share the name of the repo with your partner
* Each of you should
  * Fork your partners repo
  * Make some edits to their file
  * Make a pull request for them


