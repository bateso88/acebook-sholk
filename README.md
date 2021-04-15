# Welcome to SpaceBook
###### _In Spacebook everyone can hear you scream..._

## Description

A Facebook-inspired social messaging platform, where users can post their thoughts, like and comment on posts.

This was a team project built in two weeks as part of the Makers bootcamp. The brief was to create a Facebook clone using Ruby on Rails, a framework new to all of us. We were given a Rails project skeleton to work from.

To develop the app, we followed the client requirements in deciding what features to focus on. We took advantage of several existing gems (libraries) to simplify our work.

## Key Features

#### Sign up/Sign in

- A user can sign up to Spacebook. This is done by entering account name, email and password
- Once a user has signed up they can login and logout of Spacebook
- No two users can have the same email address or username
- An email address must be a valid email address otherwise it won't work
- When a user creates a password it must be between 6-10 characters long
- Users can update their user information once they are signed in. This includes - changing email, username and password and deleting the account.

#### Posts

- When a user signs up they are taken to the homepage of Spacebook
- A user can create a post
- A user can only create a post if you are signed up and signed in
- The post will display: the message, the username of the person posting, the date of the post and the time last edited
- Posts can have line breaks wihtin them
- A user can not write out an empty post
- Newest posts are shown first

#### Editing/Deleting posts

- A user can edit thier own posts
- A user can not edit other people's posts
- A user can only edit their own post up to 10 minutes after they have posted.
- A user can not edit thier own post after 10 minutes
- A user can delete their own posts
- A user can not delete other people's posts

#### Liking posts

- A user can like each post only once
- A user can only unlike a post after they have liked it
- When liking a post the page updates asyncronously

#### Navigation bar

- If a user is signed in, the navigation bar displays the following links:
  Spacebook homepage, Posts, New Post, Settings and Sign out
- If a user is not signed in, the navigation bar displays the following links:
  Spacebook homepage, Posts, Sign up, Sign in, New Post
- If a user that is not signed in and clicks on anything other than sign up page, they will be redirected to the sign in page.

#### Alert messages

- Depending on what the user has just done on the page, they will recieve certain alert messages at the top of their screen. e.g. If a user has just signed up they will get a welcome message on the home page or if a user that hasn't signed in tries to click on the posts page they will get an alert telling them to sign in or sign up before continuing.

## Key Contributors

Contributors to the project include Oliver Bates, Hugh Cavanagh, Salar Ghotaslo, Karsten Finlay and Louis Wickremeratne.

## Prerequisites

- Ruby on rails

## Quickstart

First clone this repo! Then:

```
> bundle install
> bin/rails db:migrate
> bundle exec rspec # make sure all tests are passing
> rails s # start the server at localhost:3000

```

## Resources

[Trello Card Wall](https://trello.com/b/9Td5gkMI/acebook-sholk)  
[Wiki - Team charter, Retros and Sprint Reviews](https://github.com/SalarGhotaslo/acebook-sholk/wiki)

## Who are we?

- [Karsten](https://github.com/KarstenFinlay)
- [Hugh](https://github.com/hacaravan)
- [Ollie](https://github.com/bateso88)
- [Louis](https://github.com/louiswicks)
- [Salar](https://github.com/SalarGhotaslo)

## Our App

- We have built a clone of Facebook as part of the Makers Academy Course.
- It's built in Rails with some Javascript on the frontend.
- It's hosted in Heroku -
  [Spacebook](https://limitless-fortress-82053.herokuapp.com)
- It has a fun space theme.
