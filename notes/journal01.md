# Journal 01

## Monday, 2019-08-26
Putting together curriculum ahead of time is not ideal process for me, I've found. I think a more fluid approach would work better. Take a top down approach with Fast.ai and supplement with bottom up ad-hoc lessons as needed.

My starting point: CS degree; professional web, C#, SQL developer; a few recent college AI courses and MOOCs; interest in brain and tech.
### Resources
  - Fast.ai
    - https://course.fast.ai/
    - took 2018 course part 1 and 2; 2019 is better good and newer
  - Google Cloud Platform
    - https://cloud.google.com/
    - 300 free hours of cloud computing
    - see [gcp setup](https://course.fast.ai/start_gcp.html)
  - The Math of Intelligence
    - https://www.youtube.com/playlist?list=PL2-dafEMk2A7mu0bSksCGMJEmeddU_H4D
    - potentially good math / ai review

## Tuesday, 2019-08-27
I'm trying new journal headings. Might be getting little carried away by amount of detail. Probably not useful. I'm taking notes not writing a book.

Research suggests hand-written notes aid memory more than typing but text is searchable. Hmmm.
### Log
- Using Ubuntu 18.04 Desktop (GNOME 3)
- Ubuntu startup in VirtualBox would display error "drm:vmn_host_log [vmugfx] ERROR Failed to send log message"; fix was to change grafphic controller from VMSVGA to VBoxVGA in VM's settings > display
- Installed Atom deb and Markdown-Preview-Plus package for journaling. Still using VIM when with terminal.
- VirtualBox 6.0 with Ubuntu 18.04 guest on external USB 3 SSD runs fine between MacOS High Sierra and Windows 10 1903; as long as guest is shut down, saved state on Win can't restart on Mac, probably other direction as well. Looking at saving application state on shutdown to restore on restart.
- Reading Stanford CS231n Module 1 Neural Networks; good refresher and they use some different terminology; like volume instead of tensor (not sure if old or new and in what context)
- Entire system slowed down. 10 Chrome tabs open, several running processes; Switched to Firefox for comparison.
- Mac captures Super key (command); Windows passes it through. I.e. More Ubuntu shortcuts available with Windows host.

### Resources
  - Stanford CS231 Convolutional Neural Network for Visual Recognition
    - http://cs231n.github.io/
    - Fast.ai lesson 1 recommended [CNN Primer](http://cs231n.github.io/convolutional-networks/)
  - Glossary of Artificial Intelligence
    - https://en.wikipedia.org/wiki/Glossary_of_artificial_intelligence

### Terminology
  - input: training setup
  - learning: training a classifier or learning a model
  - evaluation: compare true answers, true labels, ground truth to predicted
  - toy dataset: for learning, experimentation, not substantial by today's standards

## Thursday, 2019-08-29
The external SSD crashed Windows with BSD listing ExFat error. Drive was giving errors and not booting. Tried Linux tools fvck; partially fixed for awhile but then BSD. Probably caused by Mac sleep that sometimes doesn't properly sleep or eject drive. Also modified VM setting to identify drive as SSD to guest. ExFat's lack of journaling doesn't help. Restoring snapshot worked for short time then failed again.

Formatted drive NTFS and using on Windows hosts exclusively. Ubuntu OS shortcuts closely resemble Windows. Mac OS blocks Super (command) key by default. I may look into workaround if there are other reasons to move back to Mac. Do like the trackpad.

First two videos of Siraj Machine Learning playlist Intelligence of Math good overview, densley packed info. Get good overview, then search for in-depth explanations.

### Resources
  - Hands-on Machine Learning with Scikit-Learn and Tensorflow (2017; Geron; 1st)
    - https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/

## Friday, 2019-08-30

### Morning

Starting to realize that customized parallel just-in-time learning works better for me (most people?) rather than learning large blocks sequentially like traditional university curriculum.

Customized in that my breadth and depth of knowledge along with deficiencies are very specific. Parallel in that referencing multiple different sources on same topic can lead to better understanding by identifying patterns in the similarities and differences. Just-in-time in that there is so much information out there that taking months to study a math topic only to forget the details doesn't make sense when studying the concept in context is faster and leads to better understanding and more likely to be remembered.

Resources section was a good idea but not sure if spreading it out across each day is best implementation. Maybe have dedicated resources section and link from each day.

Decided to [change Ubuntu login screen color](https://askubuntu.com/questions/1089843/change-login-screen-purple-background-18-10) (purple getting old).

Atom text editor comes with built-in Markdown preview package that can display Github style. Added [markdown-scroll-sync][11] to keep preview window in view. Atom is complaining of '1 deprecation' but package is most current.

You can get title image of youtube video like this `http://img.youtube.com/vi/place-video-id-here/0.jpg` For example, [SVM video title image](http://img.youtube.com/vi/g8D5YL6cOSE/0.jpg).

### Evening
I think I've been taking too many detours. Spent some time writing SVM from scratch in Python, which was good exercise but delaying Fastai course.

Watched [Lex Fridman's interview of Jeremy Howard][12] and impressed with practical approach. My goal should be to dive into Fastai course, learning as necessary. I can revisit related topics later to round out my knowledge.


## Sunday, 2019-09-08

Have been reading Deep Learning book 2016 by Goodfellow. Very good coverage of deep learning from overview of history to 2016. Includes primer on Linear Algebra.

Instead of meticulously logging learning journey and trying to memorize everything along the way, I'm switching to practical tasks and learning enough to achieve results. Jotting down concepts and links makes sense for personal reference. Detailed explanations or opining seems unnecessary.

- Fastai Lesson 2
- Deploying to [Render](https://course.fast.ai/deployment_render.html)
  - Free static projects
  - $7/month lowest tier for Docker
- Installed Docker ran Teddy project local
- Google Cloud App Engine
  - [Fastai on GCP App Engine](https://course.fast.ai/deployment_google_app_engine.html)
  - created new project
  - problem with sample project from pankymathur server.py
  - replaced with [Render repo](https://github.com/render-examples/fastai-v3) and changed port from 5000 to 8080 (5000) caused 502 Bad Gateway error in Google App Engine
- Next
  - practice lesson 2
  - download images and create custom model
  - deploy custom model to app engine













[end]
