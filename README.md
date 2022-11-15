# Sarcasm-and-Hate-in-comments-for-fake-News-Detection
Sarcasm and Hate in comments for fake News Detection

**Tweets.tsv file:**
This file contains the features we used during our experiment related to the tweet file:
  - Tweet IDs
  - Label: Whether a tweet is False or True
  - Has_reply: 1 if a tweet has replies, 0 if not
  - Sarcasm: 1 if a tweet is sarcastic, 0 if not
  - Contains_Hate: 1 if a tweet is hatful, 0 if not
  - number_of_replies
  - Sarcasm_mean: The average of sarcastic comments replying to each tweet
  - Hate_mean: The average of hateful comments replying to each tweet
**Comments.tsv file:**
This file contains the features we used during our experiment related to the replies file:
  - Tweet IDs: The tweet a particular comment is replying to
  - reply_id: The comment ID
  - Sarcasm: 1 if a comment is sarcastic, 0 if not
  - Contains_Hate: 1 if a comment is hatful, 0 if not
