# API_Practice
## Twitter API
**Focus**
The API practice is a start of using twitter API.
This part serve as a practice of generating API token, URL, and fetching my own tweets form twitter server.

## Google API
The google cloud natural language API practice is merged into the final of sentimental analysis.
## Sentimental analysis
**Product:**

Extract tweets about one topic and return people's view and feeling about it.

**User story:**

1. Event organizer: want to provide better event and earn more money
   1. Analyze people's view towards the event to see costumers' attitude. 
   2. Return the most frequent mentioned point in the tweets, and costumers' view about it, determine if it is a highlight or it need to be improved.
2. Costumer: want to avoid low quality event and save money
   1. View people's attitude toward an event, match, concert, etc. , before purchasing the ticket to them.
   2.  Write view about events by sending tweet, and the attitude in tweet can affect organizer and other costumer.

**Minimum Valued Product:**

1. Extract tweets.
2. Analyze tweets using Google NLP API.
3. Return the feelings people mostly feel about one topic.

**Modular Design**

1. Front: A Linux version for enterprise use and a mobile version (IOS, Android) for individual use.
2. Cloud computing: 
   - For individual version none cloud server computation is provided. The amount need for calculation and storage is small and can be covered by local device.
   - For enterprise user, cloud server deployment is provided. Google cloud server or AZURE can provide strong server for large quantity data processing capability.

3. Storage:
   - For individual version, storage is at local, but we provide user a cloud backup of their daily analysis user data. 
4. Data encryption:
   - The front shall be able to encrypt user data before updating them to the server. 
   - The server shall be able to decrypt data to process and encrypt data and analysis for return.
5. Following with twitter topic and event
   - Both individuals and enterprise user shall be able to follow the sentimental analysis of one topic or event. They shall not being required to re-enter information again and again.
