# Build Twitter

## Requirements clarification
- **Functional requirements**
   - Post: Users can post tweets.
      - Tweets can contain photos and videos.
   - Follow: Users can follow other users.
   - Timeline: System should be able to create and display a user’s timeline consisting of top tweets from all the people the user follows.
- **Non-functional requirements**
   - High availability.
   - Acceptable latency of generating timeline is 200ms.
   - High consistency is desirable (It should be ok for a user doesn’t see a tweet for a while).

## Estimation
- **Traffic estimation**
   - Our system will be read-heavy.
   - Users
      - 1 billion users. (Assumed)
      - 200 million daily active users. (Assumed)
      - 100 million new tweets every day. (Assumed)
      - Each user follows 200 people on average. (Assumed)
- **Storage estimation**
- **Bandwidth estimation**