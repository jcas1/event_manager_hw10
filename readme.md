[Issue 1](https://github.com/jcas1/event_manager_hw10/issues/3) default /register/ execution returns 500 internal server error 
[Fixes for Issues 1](https://github.com/jcas1/event_manager_hw10/pull/5/commits/dea7475afa84812a7aae90818c14a472d066188b)

[Issue 2](https://github.com/jcas1/event_manager_hw10/issues/4) request body for the default registration shows incorrect profile picture link
[Fixes for Issues 2](https://github.com/jcas1/event_manager_hw10/pull/6/commits/488f3c4c7d1434f0187dd109a2f8fe135df3851f)

[Issue 3](https://github.com/jcas1/event_manager_hw10/issues/7) get user not returning all relevant information
[Fixes for Issues 3](https://github.com/jcas1/event_manager_hw10/pull/10/commits/c0053e6f174a8b250b303a43e556a4669001a655)
[Fixes for Issues 3](https://github.com/jcas1/event_manager_hw10/pull/10/commits/645c64f8bb9b39d25ad8a5229d2d1e8913b76332)

The issues fixed in professors video where already addressed in the repo. 

Picture of Docker Hub
[image](<images/docker image hw10.png>)

Picture of Pytest Coverage
[coverage](<images/pytest coverage hw10.PNG>)

Summary:
I found this assignment to be somewhat of a reality check for me. Since I do not have much programming experience, a code base like this felt hard to go through. When I experienced my first issue, regarding the internal server error, I was not sure of where to start in regards to fixing it. It was through shifting through the pgadmin, fastapi and postgres, logs where I found that some columns were missing. Adding the columns and adjusting the code slightly I was able to fix the issue and move on to others. I patched up more obvious issues, similar to the video, but after that I felt like I had a hard time trying to find issues, that I could fix. I did the basic, password stuff like expecting number and special character requirements, but they seem to be accounted for. Unique usernames also seem like they were already accounted for. 

However, this assignment did feel like a good learning experience, in a way where it showed me what I don't know, and what steps to take in terms to of filling up the large knowledge gap I have. This assignment showed me how robust a program and understand the value of programmers. 