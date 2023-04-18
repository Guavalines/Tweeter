![Tweeter](https://user-images.githubusercontent.com/100665876/232444976-a54d7c5a-374a-4ca9-8d35-fe516d6b7735.png)


## Description

TWEETER is a Twitter clone with Rails 7, featuring dynamic stat updates, polymorphic liking of comments and tweets, comment controls, turbo-comments, retweets, real-time tweet deletion, profile pages, and turbo-fied tweet creation.


## Features

- Basic CRUD for tweets
- User profiles
- Users can leave comments on tweets, with the ability to delete their own comments.
- Users can "like" both tweets and comments, with a polymorphic "like" feature that enables code reuse. Stats such as comment counts and retweet counts are updated accordingly.
- Users can take action on their tweets using various controls, including the ability to delete their own tweets.
- Users can retweet tweets from other users, creating a new tweet with a reference to the original author.
- Uses Devise gem to create a user authentication system, which ties tweets to user accounts. Only authenticated users can author tweets.

## Views
![Screen Shot 2023-04-15 at 12 54 41 PM](https://user-images.githubusercontent.com/100665876/232250749-688b9ab4-e9bb-4831-b43b-fb9b3635d460.jpeg)

![Screen Shot 2023-04-14 at 12 14 28 PM](https://user-images.githubusercontent.com/100665876/232137069-6a6c72f5-17c5-4bfd-8ec7-dcf920a943b7.jpeg)

![Screen Shot 2023-04-14 at 12 14 42 PM](https://user-images.githubusercontent.com/100665876/232137391-9c5c0905-86bd-40db-afbe-8ee38e61e400.jpeg)

![Screen Shot 2023-04-14 at 12 15 33 PM](https://user-images.githubusercontent.com/100665876/232137552-49e2252f-3df9-4b94-af44-87fa62bcdd25.jpeg)

## Please initialize these before starting the app:

### Versions


![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white) 3.0.3p157 (2021-11-24 revision 3fb7d2cadc) [x86_64-linux]

![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white) 7.0.4.3

### Tools Used

![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)


### Setup

```
 git clone git@github.com:guavalines/Tweeter
.git
 cd Tweeter
 rails db:create db:migrate db:seed:replant
 bundle install
 yarn install
 rails server
```

Open you browser and visit localhost:3000





