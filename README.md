# *SimpleTweet*

**SimpleTweet** is an Android app that allows a user to view his/her Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **11** hours spent in total

## SimpleTweet Part 2

### User Stories

The following functionality is completed:

- [x] User can **compose and post a new tweet**
  - [x] User can click a “Compose” icon in the Action Bar on the top right
  - [x] User can then enter a new tweet and post this to twitter
  - [x] User is taken back to home timeline with **new tweet visible** in timeline
  - [x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  - [x] User can **see a counter with total number of characters left for tweet** on compose tweet page
  - [x] User can **pull down to refresh tweets timeline**
  - [x] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.com/android/Using-Parceler).

### Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/8ccUUIyX7oDqEDRBRr/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Giphy](http://www.giphy.com).

### Notes
One challenge encountered while building this app was showing the character count as a tweet was composed; a new dependency and support library was added to Android Studio to incorporate this functionality using a TextInputLayout instead of ConstraintLayout for the Compose activity. 

## SimpleTweet Part 1

### User Stories

The following functionality is completed:

- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
  - [x] User is displayed the username, name, body, and user profile image for each tweet
  - [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh

### Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/3E2PlvWBmZYIGacwHg/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Giphy](http://www.giphy.com).

### Notes

Importing the RestClient Template and showing the timestamp for each tweet based on the information provided in Twitter's API were some of the challenges encountered while building SimpleTweet. I had to update Android Studio and implement the code to parse a relative twitter date, among other functionalities, to create a holistic Twitter app.  

### Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

### License

    Copyright [2019] [Isha Kabra]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
