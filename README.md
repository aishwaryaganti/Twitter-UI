# Twitter Clone

## How to run

Do the following:

```
git clone
npm install
npm start
```

## Application Scope

This application takes following this as assumptions to define the scope of the solution:

```
1. Features supported by current application: LIKE , TWEET, COMMENT, CHECK TWEETS OF YOUR FOLLOWERS.
2. Grouping tweets by conversations and retweeting is NOT IMPLEMENTED
3. All tweets are considered public.
4. Support for localization and personalization is not part of the current scope.

```

## JSON Data format

Below is the static Data format used with in this application to implement the assumed featues.

```js
{
  tweets: {
    tweetId: { tweetId, authorId, timestamp, text, likes, replies, replyingTo},
    ...
    ...
    ...
  },
  users: {
    userId: {userId, userName, avatar, tweets array},
    ...
    ...
    ...
  },
  authedUser: userId
}
```
