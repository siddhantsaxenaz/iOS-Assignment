# Trial Week : Assignment (Rahul Kumar Tyagi)

**Assignment**

Implement an API driven interface for Your Library of videos which shows Your profile as the first tab and then shows a dynamic number of tabs from channels which you have subscribed to.

All the primary tabs will have dynamic sub tabs. Subtabs can be one of these depending on the response of the API
- Home 
- Videos 
- Playlist 
- About

The tabular interface should look  exactly like “Your library” tab of Spotify
![](https://i.imgur.com/x6RJHdo.png)
(Spotify’s Your Library Tab Interface)

**Details of required implementation**
- Use youtube’s API  (https://developers.google.com/youtube/v3/getting-started) to populate tabs and sub tabs dynamically.
- Fist Tab should always be user’s Own Profile and following tabs should be the channels which the user has subscribed.
- Subtabs can be dynamic depending on the main tab. 
- Scrolling tab bar animation and transition implementation. 
	- Size of the scrolling bar changes as we scroll from one sub tab to another according to the size of the text of the sub-tab title.
	- Color of the sub-tab title changes as the scrolling bar moves.
	- When a user scrolls the scrolling bar and scrolling bar is at the last sub-tab then it changes the main tab with a similar interaction as the sub-tabs.
- Every subtab is a collection of videos. The interface of the sub tab should appear exactly like the above interface of Spotify’s snippet. It should have the following components
	- Image - Video thumbnail
	- Title  - Title of the video
	- Subtitle - other important information about the video


The above assignment will be assessed on the basis of the following criteria
1. Code quality and modularity.
2. Dynamic behavior of the interface.
3. The final output quality of UI Implementation.
4. Code architecture.
5. Bug-Free implementation.


**Brownie Points**
1. UI test cases.
2. Real-time dynamic tab update.
3. Space and time management of the implementation. 
4. Don't use storyboard or xibs for UI implementation, create all views using autolayout.
