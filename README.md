# Builds

Repos with source code:

https://github.com/avdvplus/CoreELEC

https://github.com/avdvplus/linux-amlogic

https://github.com/avdvplus/media_modules-aml

https://github.com/avdvplus/service.coreelec.settings

https://github.com/avdvplus/xbmc


MESSAGE BOARD:

I heard about the chatter in regard to my repos and commits on different forums, I explained what I did on cpm's GitHub private repo discussion forum but it seems there is still some confusion from the people that were part of that forum and of course there are people that were not part of cpm's GitHub private repo discussion forum. So let me attempt to explain again - first, of course I have my code on a "git", there is no way to manage changes on a project of CoreELEC's system size without one, but I do not use GitHub, I have quotes around the word "git" because what I use is really not a git but my own software versioning tool I developed as part of a team a very long time ago. This software does not have any links/connections/APIs to GitHub or related gits. So there is no way for me to move my deltas/changes to a GitHub git commit format in a correct and detailed way.

I do use different GitHub repos to cherry pick, do diff compares, etc... but it is not the true source of my code. When I tried to have my changes ported from my tool to GitHub commits format the repos became unmanageable and incomprehensible (the correct technical term - a big mess). Besides my local code (on my tool) or my official GitHub repos where I publish my Builds and code, all other GitHub repos I use are temporary/staging/incorrect/incomplete because of the way I use them.

What I did when I published my first build/code release (R1) was to fork cpm's repos, delete everything on the directories except of course the .git directory and then move my code into those directories and create one commit. So up to that point before my commit, if you compare my repo with cpm's repo it will be identical, of course, the .git is the same up to that point. After my first large R1 commit of course it is different. From R1 on I am doing the same way for all my new releases, just collect all the files that changed from one release to the next and moved it to my GitHub repos, given my tool, that is the only sane/practical way I can have my full code public. Unfortunately, for me there is no other practical way to do it.

To answer another common question I see on different forums, I did not start my development with cpm's repo but with the CoreELEC original repo although I ported a large amount of cpm's code to my build (as much as I could without creating a conflict with my own code). At this point in time, this really does not matter because cpm also started with CoreELEC originally and now we are closer to each other build's than the original CoreELEC (of course in regards to cpm's 21.3 repos). I used forks of cpm's repos to publish my code so cpm could more easily see the differences from his code and mine and pull whatever he wanted, he has been doing that and I continue porting code from his repos to mine. Of course, I use much more of his code than he uses of mine.

Some more info on my builds, I do not use any AI to develop any of my code or my release notes, a few times I used AI to validate what I coded but very few times. Also, I have my profiles private because I learned a long time ago that "no good deed goes unpunished", as it is the case now with people jumping to conclusions about my repos and commits, so I prefer not engaging in drama. I do not make any money with my builds work, I do not accept any donations for my builds work, I spent a large amount of my time improving features that I cannot even use. As an example, I do not own or use a S905X4 SoC device, but I spent a large amount of time improving the media playback and fixing issues with the S905X4 SoC for the benefit of the S905X4 owners. Actually, I spent my own money, and more importantly, my limited time to develop and share my build and code to the benefit of the CoreELEC/Kodi community.

The best way to contact me is through my GitHub Builds repo Issues page. Although I participate in a few forum discussions every so often, I prefer staying out of the fray and having productive/constructive discussion one-to-one or in a small group setting. This is the introvert in me, but a little about myself, I am a Hardware and Software Engineer with more than 45 years of experience and still working. Ah, almost forgot, in regard to the rumor that I am Russian. I am not Russian, if I was Russian I would be a better coder.

