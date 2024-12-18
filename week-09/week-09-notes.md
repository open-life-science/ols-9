
# Week 09 - Tooling for Collaboration: Open-source software in practice

* Date: November 13, 2024
* Time: 16:00 (UTC) [https://arewemeetingyet.com/UTC/2024-11-13/16:00](https://arewemeetingyet.com/UTC/2024-11-13/16:00) 
* Duration: 90 min
* Call lead: Tajuddeen Gwadabe
* Facilitator: Pradeep Eranti

## 🗣️Join the Cohort Room and Welcome

Tajuddeen (10 min)[⏰ 10]

Are you an Open Seeds participant but can't attend this call? The recording from this call will be updated on YouTube: [https://www.youtube.com/c/OpenLifeSci/playlists](https://www.youtube.com/c/OpenLifeSci/playlists)

* Code of conduct and community participation guidelines [https://we-are-ols.org/code-of-conduct](https://we-are-ols.org/code-of-conduct)
   * If you experience or witness unacceptable behaviour, or have any other concerns, please report it by contacting the organisers - Bérénice, Malvika, Yo and Taj. (team@we-are-ols.org).
   * To report an issue involving one of the organisers, please email one of the members individually (berenice@we-are-ols.org, malvika@we-are-ols.org, yo@we-are-ols.org, tajuddeen@we-are-ols.org).

* This call is being recorded and transcribed!
   * The video will be available on the YouTube channel ([https://www.youtube.com/c/OpenLifeSci)](https://www.youtube.com/c/OpenLifeSci)) in the next days
   * Turn on your webcam if you don't mind sharing your face (or off if you do!)

* Where to indicate preference? --* In your Zoom name*
       * You can edit your Zoom name directly (click on the three dots on the top right of your video) and add one W or S letters in front of your name
   * Please let us know in the chat your preference for the breakout room today - a co-host will edit your name to add one of these letters:
   * If you are ok with both, please choose one for this week so that the hosts can assign you to a breakout room during the cohort call

## At the end of this week's cohort call, you will be able to:

   * Apply good coding practices to your software
   * Review code
   * Identify package management for your software
   * Make your software ready for open-source

## 🌍 Icebreaker question

*Name / What's something beautiful you encountered about nature or the world recently?*
   * Bastian / I literally moved from Europe to Argentina 2 days ago and love having a second summer this year!
   * Tajuddeen / some rare type of bee is stopping META from starting a nuclear power station
   * Oluwatoyin (W)/early sunset and total darkness by 5:30 pm as we move into winter
   * Soorena / Observed turbulence in everyday phenomena such as surf and fast-flowing rivers
   * Nooshin /  Even though we haven’t had snow yet in Winnipeg, I’ve noticed how the mornings are mistier, and the air feels crisp—it’s like nature’s hint that winter is just around the corner.
   * Olaitan, the weather changing into the Winter gradually and the transition is great.
   * Nishith / reconnecting with the sound of silence.
   * George: The beautiful waves of the Indian Ocean
   * Faisal: I feel sleepy as I took a journey from Addis Ababa to Vancouver via Thailand and the Philippines, with 21 hours of flight and 28 hours of layovers, sounded like an exciting adventure, but it was tough on the body and mind.
   * Wesley Sanchez - Fall colours in the NE
   * Vrinda /hiking in the fall 
   * Amy / walking in the rain and looking at all of the changing leaves and fallen leaves - the colours are so beautiful
   * Lulwama /cats and sunshine
   * Clotilde /The beauty of sunshine ☀ 
   * Anemily  / small cats
   * Kaitlyn / fall colours; walks by the Thames River
   * Brevin /Enjoying the balance of rainy and sunny days 
   * Musanna / Fall colours in north cascade
   * Jaimie / Rainy weather. I'm a pluviophile. 
   * Jackie / My plants recovering from my neglect and blooming again!
   * Arra / the autumn leaves still on trees on the mountain 
   * Alfredo / Summer arriving to Argentina, so it is quite warm and sunny.
   * Yuwei / maple trees in the fall
   * Pradeep  / OLS is growing with nice people :) 
   * Ahlam / Sunny days are perfect for the mood
   * Chiedozie / Waterfall
   * Alex  / I greatly appreciate the green landscape of Cali, Colombia
   * Fatou  / Seeing indoor plants out in their natural environment
   * Chika /Falling of the leaves
   * Gracielle  / I saw a video of a salmon swimming up a river this week!
   * Linda /fall in Canada

## 🖥 Talk: Open-source software in practice

[Tajuddeen] (5 min) [⏰ 15]

Presenter:
* Contact / social:
* Slides: [https://docs.google.com/presentation/d/e/2PACX-1vRvZgO4mhul2N575YsayBI1EFDmCIneKg47A9YAXRS8PMafLUgQ8s3COoL86I6XuQ/pub?start=false\&loop=false\&delayms=3000](https://docs.google.com/presentation/d/e/2PACX-1vRvZgO4mhul2N575YsayBI1EFDmCIneKg47A9YAXRS8PMafLUgQ8s3COoL86I6XuQ/pub?start=false\&loop=false\&delayms=3000)

## 🖥 Talk: Code Review

[Pradeep] (15 min) [⏰ 30]

* Presenter: Bastian Greshake Tzovaras
   * Contact / social: bgreshake@proton.me / @gedankenstuecke@scholar.social
   * Slides: [https://docs.google.com/presentation/d/1ybkgxS1W4\_6cDakrEin3R7LYqYrUSWdLHErFsuyfsSY/edit?usp=sharing](https://docs.google.com/presentation/d/1ybkgxS1W4\_6cDakrEin3R7LYqYrUSWdLHErFsuyfsSY/edit?usp=sharing) 

Notes:

   * Code review is a good way to help improve the efficiency of the code
   *   
 
**Questions**

* Is technical documentation a part of the reviewing process?
       * Yes, it can be if one sets that expectation. Especially for changes to the code that add new features etc. Then reviewing the documentation to make sure it still fits the new features is important
   * Any training sessions organized in the R/Python/.. communities available for How-to code review?
       * Not aware of any formal tests, but: 
           * 1. one can do "pair-reviewing", where one can review with someone that already has experience reviewing,  similar to how researchers learn academic peer review by doing it with someone more senior for the first few times
           * 2. as everything is transparent, one can read over past code reviews to see how people interacted and learn from those 
   * How does testing and reviewing differ?
       * Reviews target things like efficiency/speed, readability and other aspects that tests can't cover as there are many ways to solve any problem in programming. also: tests are also written by people, so we need to review those!

## 🖥 Talk: Good Coding Practices

[Tajuddeen] (15 min) [⏰ 45]

* Presenter: Olaitan Awe
   * Contact / social: @laitanawe
   * Slides: [https://docs.google.com/presentation/d/122OcEk4tYbo5ZI4isS4KbOYxGFiTBesR/edit?rtpof=true](https://docs.google.com/presentation/d/122OcEk4tYbo5ZI4isS4KbOYxGFiTBesR/edit?rtpof=true)

* Notes:

   * Good code is easy to maintain, extend and build upon!
   * Workflow management systems for reproducible coding
   * It's important to have your code accessible and findable, and to add documentation such as a README and a license
   * Good idea to have a notebook for demonstration!  
   * [https://www.asbcb.org/](https://www.asbcb.org/) - African Society for Bioinformatics and Computational Biology

Questions
   *  Any examples of good coding practices?
       * Good code improves collaboration, debugging, and testing, while reducing long-term costs.
   * When to decide whether to modularize the code or just run the commands directly? Complex (RNA-seq pipelines) vs. simple tasks.

## 👥 Breakout discussion: Bug in a scientific tool

[Pradeep] introduces, [Tajuddeen] makes breakouts (15 min) [⏰ 60]

15 minutes, ~3/4 ppl per room

### Instructions for the room

Think about a bug you've encountered in a scientific tool, either as a writer or a user. Was the software/code open, and if not, could openness have made a difference?

### Directions for written discussion rooms:

* Each room will be assigned 3/4 members
   * Please agree if you use either this document or the Zoom chat
   * Each member will take 2.5 minutes to write down their response
   * In the next 5 minutes they will read through and comment on each other’s notes either on this document or on Zoom chat

### Notes from breakout discussions

Breakout Room 2 - Written

* Names: Fatou, Kaitlyn, Wesley, George
   * Notes
       * Wesley writes software so he runs into them daily. 
       * George has no coding experience. He's designed apps however that had many bugs over the course of development
       * For her masters thesis Fatou is am designing a python experiment for eye tracking. I am dealing with many bugs however don't plan on making the tool open until after my thesis is submitted. I am sure once it's public people might find bugs I did not catch. If I had time, I would publish it for review prior to starting the experiment.
           * George: a lot of my projects are private which delays identifying bugs. The collaborative projets which are open-source always have more transparency and makes finding/fixing bugs easier. However, they also have more moving pieces so there often are more of them.
       * As a Comp Sci PhD student, Kaitlyn encounters a bugs in her own code. Aside from that, she finds a lot of open repositories, especially for deep learning models, have bugs or are incomplete. So she thinks having a more rigorous code review process (maybe an extra stage in the paper review process) would be helpful.
Breakout Room 3 - Written

Breakout Room 5 - Spoken

* Names: Linda, Brevin, Nooshin 
   * Notes
       * One example of a bug I've come across in scientific tools relates to data visualization libraries in Python, such as Matplotlib. There was an issue with legends overlapping with plots when generating complex graphs involving multiple subplots and custom layouts. This bug was particularly frustrating when it came to presenting clear and readable figures for publications.
       * Matplotlib is open-source, which significantly impacted the ability to resolve the issue. Openness in this case made a substantial difference because:
       * Being open-source meant that I could read through the codebase and documentation to understand how legend positioning was handled and identify potential workarounds.
       * In working with a semi-open source software for a license plate recognition application, I encountered a significant challenge with video frame positioning. Specifically, the software was not capturing the video feed with the frame aligned correctly, resulting in portions of the license plates being misaligned or out of view. This misalignment disrupted the recognition accuracy, a critical aspect of the application's functionality. Due to the software's semi-open nature, access to the full codebase was restricted, limiting the ability to directly troubleshoot or modify the underlying frame handling and positioning code. Although configuration settings were available, they were insufficient for resolving this issue fully. If the software had been entirely open-source, examining and adjusting the code responsible for video capture and frame alignment would have likely expedited troubleshooting and improved the accuracy of the license plate recognition process.
       * No skills in coding, but currently undertaking the short course in python

Breakout Room 9 - Written

   * Names: Gracielle Hingino, Anemily Machina, Mirta Dumancic
   * Notes
       * Sustainability and maintenance are overlooked topics in Open Science
           * Being open helps when older research tools are abandoned, and other people can take over and update the tool
       * How to deal with proprietary dependencies in open source software?
Breakout Room 10 - Spoken

## 🖥 Talk: Package Management

[Pradeep] (15 min) [⏰ 75]

Presenter: Ruth Nanjala

   * Contact / social: Twitter: @Ruthnanje LinkedIn: Ruth Nanjala
   * Slides: [https://docs.google.com/presentation/d/1ewt5jgfs7q5xO\_fMOmoT08sV4iMGBNV\_/edit#slide=id.p1](https://docs.google.com/presentation/d/1ewt5jgfs7q5xO\_fMOmoT08sV4iMGBNV\_/edit#slide=id.p1)

* Notes:
   * Creating environments for your software will help in making it usable in different contexts and they carry all the dependencies within them
       * Software environments are like water bottles - you can carry your bottle of water anywhere and it contains what you need within it; when developing a software, you need to make sure to pack everything within a "bottle" that you can carry anywhere
       * They are also called package maintainers and containers
           * Docker and Singularity use images to run containers

## 🗣️ Closing

[Tajuddeen] (5 min) [⏰ 90]

### Assignments

* Mid -cohort survey: [https://forms.gle/q97BPjwmx2X2v6Qq6](https://forms.gle/q97BPjwmx2X2v6Qq6)

### Have any questions?

Add them below. We will respond to these on Slack and also share them via an email
   *  

### Feedback about this call:

What worked?

   * The time tracking was excellent!

Licence: CC BY 4.0, Open Seeds by OLS, 2024










