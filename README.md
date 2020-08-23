# warmups

## When using different machine

1. check for the last name and email by the commands:
`git config -- global user.name`
`git config --global user.email`

2. delete the last credentials for that username and email by the commands:
`git config --global --unset user.name "the appeared username"`
`git config --global --unset user.email "the appeared email"`

3. on Mac desktop search for “keychain”, search for any Github account and delete it.

4. set your credentials using the following command:
`git config --global user.name “YOUR_GITHUB_USERNAME”`
`git config --global user.email “YOUR_EMAIL_ADDRESS”`

## First time work

1. Fork the required warm up repo ( check slack to see link ).

2. From your Terminal, clone the _forked_ repo to your local Desktop, (you can find it in your Github repositories).
`git clone https://github.com/[YOUR_USERNAME]/[REPOSITORY].git`

3. From your terminal, Navigate to _the forked repo_.
`cd [REPOSITORY]`
example: `cd rbktn07-warmups`

4. Create a new remote locally by running this command in your terminal:
`git remote add [REMOTE_NAME] [REMOTE_LINK]`
_example:_ `git remote add upstream https://github.com/hackreactor/rbktn07-warmups`

5. Read the question, solve it, and save.

6. Use git status to check the changed files.
`git status`

7. Stage the changes of the file.
`git add [FILE_NAME].js`

8. Commit your changes
`git commit -m “YOUR_MESSAGE”`

9. Push your code to your GitHub account
`git push origin master`

10. share your solution with the administration:
From your forked repo in your Github account, select Pull Requests and then click on create a New pull request.
**STOP.** Before you Click to create a pull request for this comparison you must adjust the target branch (aka base branch) to be your username. Once changed, the pull-request heading should look like this:
_base repository:`hackreactor/rbktn07-warmups` base: `YOUR_BRANCH` <- head repository: `YOUR_USERNAME/rbktn07-warmups` compare:`master`_

11. Click Send pull request

## Daily work

1. Check the git conf
If you are using a different machine, repeat the steps mentioned above (without forking again ).

2. Get the new daily warm up by pulling it from the remote.
`git pull [ORGANIZATION_REMOTE_NAME] [BRANCH]`
example: `git pull upstream master`

Note: if you can’t remember your remote name, use the following command to know
`git remote -v`

3. Read the new warm up exercise, solve it, and save.

4. Use git status to check the changed files.
`git status`

5. Stage the changes of the file.
`git add [FILE_NAME].js`

6. Commit your changes
`git commit -m “[YOUR_MESSAGE]”`

7. Push your code to your GitHub account
`git push origin master`

8. share your solution with the administration:
From your forked repo in your Github account, select Pull Requests and then click on create a New pull request.
**STOP.** Before you Click to create a pull request for this comparison you must adjust the target branch (aka base branch) to be your username. Once changed, the pull-request heading should look like this:
_base repository:`hackreactor/rbktn07-warmups` base: `YOUR_BRANCH` <- head repository: `YOUR_USERNAME/rbktn07-warmups` compare:`master`_

9. Click Send pull request

10. You are all done.