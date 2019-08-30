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
Starting to realize that customized parallel just-in-time learning works better for me (most people?) rather than learning large blocks sequentially like traditional university curriculum.

Customized in that my breadth and depth of knowledge along with deficiencies are very specific. Parallel in that referencing multiple different sources on same topic can lead to better understanding by identifying patterns in the similarities and differences. Just-in-time in that there is so much information out there that taking months to study a math topic only to forget the details doesn't make sense when studying the concept in context is faster and leads to better understanding and more likely to be remembered.

Resources section was a good idea but not sure if spreading it out across each day is best implementation. Maybe have dedicated resources section and link from each day.

[[resources]]

[resources](resources.md)

















[end]
