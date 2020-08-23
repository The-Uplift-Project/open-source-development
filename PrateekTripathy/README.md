# Open Source Development

This repository should only be used to submit materials realated to your project like codes, reports, project ideas etc under the Uplift Project.

## Submission Procedure

Read the following steps and guidelines properly for proper submission of your project. Missing out any step or performing it wrongly can lead to unsuccessful submission.

# Steps

1. Fork this repository to your profile.

2. Clone the repository.

2. Change to your team branch by typing `git checkout <teamname>`

3. Make the changes and commit to the same branch and push it.

4. Create a pull request from `<username>/<teamname>` to `The-Uplift-Project/<teamname>`

## NOTE

DO NOT COMMIT TO THE `master` branch. Only commit to your team branch.

### Each branch will contain

-   A text file that contains proper documentation. The documentation should contain:
    -   A description of your project.
    -   The contents of your project directory.



# Chat app usinng Socket.io

Extension of the previous chat app using Socket.io.

## To run this app locally, point to the folder and

```
$ npm ci
$ npm start
```

And point your browser to `http://localhost:3000`. 

I have also deployed it on Heroku `https://chatapp-by-prateek.herokuapp.com/`

## Features I have added

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.