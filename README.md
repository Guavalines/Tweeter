# TWEETER

### Overview of Main Features:


Basic CRUD for Tweets: The app features basic CRUD principles, allowing users to create, read, update, and destroy tweets.

User Authentication: The app uses the Devise gem to create a user authentication system, which ties tweets to user accounts. Only authenticated users can author tweets.

User Profiles: The app includes user profiles, which display a given user's tweets and profile image.

Tweet Controls: Users can take action on their tweets using various controls, including the ability to delete their own tweets.

Retweeting: Users can retweet tweets from other users, creating a new tweet with a reference to the original author.

Comments: Users can leave comments on tweets, with the ability to delete their own comments.

Likes: Users can "like" both tweets and comments, with a polymorphic "like" feature that enables code reuse. Stats such as comment counts and retweet counts are updated accordingly.
