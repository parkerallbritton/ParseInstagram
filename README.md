# Project 3 - *ParseInstagram*

**ParseInstagram** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can sign up to create a new account using Parse authentication.
- [x] User can log in and log out of his or her account.
- [x] The current signed in user is persisted across app restarts.
- [x] User can take a photo, add a caption, and post it to "Instagram".

The following **optional** features are implemented:

- [ ] User sees app icon in home screen and styled bottom navigation view
- [ ] Style the feed to look like the real Instagram feed.
- [ ] After the user submits a new post, show an indeterminate progress bar while the post is being uploaded to Parse.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/W4ZsWpU.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Development was a hassle. Monday evening I sat down to finish up and submit the app with plenty of time (about 3 and a half hours) to get through the final two videos.
However, I discovered I could not get my app to navigate out of the LoginActivity into MainActivity. Around this same time, I discovered the my project's directory was inside of last week's unit's directory the whole time.
I decided to move it. This was a poor choice that set me back about 2 hours. It took forever to get the app to work again at all. Upon finally fixing this, I discovered this was not the problem.
I had apparently not added a dependency/permission (I don't remember which) that was necesarry for https communication. Yes, a literal single line of code kept me stumped for an hour.
This is the reason this app is late and the reason it took me so long in total to configure and run properly. 

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
