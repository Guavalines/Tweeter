# TWEETER

### Main Features:


- BASIC CRUD FOR TWEETS: Users may create, read, update, and destroy tweets.

- USER AUTHENTICATION: Uses Devise gem to create a user authentication system, which ties tweets to user accounts. Only authenticated users can author tweets.

- USER PROFILES: Includes user profiles, which display a given user's tweets and profile image.

- TWEET CONTROLS: Users can take action on their tweets using various controls, including the ability to delete their own tweets.

- RETWEETING: Users can retweet tweets from other users, creating a new tweet with a reference to the original author.

- COMMENTS: Users can leave comments on tweets, with the ability to delete their own comments.

- LIKES: Users can "like" both tweets and comments, with a polymorphic "like" feature that enables code reuse. Stats such as comment counts and retweet counts are updated accordingly.
