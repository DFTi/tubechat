(Please ensure the candidate arrives with a development environment ready for TDD on rails 4)

# DFTi Technical Interview

You have 1 hour to work on this task. If you don't finish by then, that's OK. You may use the internet for help/research.

# Task 

Build a Rails 4 application that:
* has a root view with thumbnails of the latest soccer videos from youtube
  - https://gdata.youtube.com/feeds/api/videos?q=soccer&orderby=published&start-index=11&max-results=10&v=2&alt=json
* clicking on a thumbnail takes the user to a chat system whereby:
  - the youtube video itself is embedded
  - a "user list" is shown displaying how many people are on the page, to everyone on the page. **Do not implement an actual user system, just generate random numbers tacked onto 'guest' for now for the sake of time**
  - implement a live chat to be had by the users on the page.
  - *BONUS* only the operator (user to first join the page) has control of the video, i.e. seeking, pausing, playing, etc will happen for all the other users as well.
  - *BONUS* implement a system whereby the operator (starts out as the first user on the page) can pass operator status to any other user in the user list


Primarily I'll be looking at how you managed your time with regards to writing tests, as well as what technology choices you made, since there are several for implementing the above. 

Try to commit often.

Good luck!