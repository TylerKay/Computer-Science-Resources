# Resources within Computer Science

# Table of Contents
- [Overview of motivation](#overview-of-the-purpose-and-motivation)
- [Valuable Resources](#valuable-resources)
- [Software Engineering](#software-engineering)
    - [Web Development](#web-development)
        - [My Web Development Journey](#my-web-development-journey)
        - [Web Development Resources](#web-development-resources)
    - [Data Structures and Algorithms](#data-structures-and-algorithms-dsa)
    - [Other Software Engineering Resources](#other-software-engineering-resources)
- [Data Science](#data-science)
- [Cybersecurity](#cybersecurity)
    - [Cybersecurity Youtubers](#cybersecurity-youtubers)
    - [Cybersecurity News](#cybersecurity-news)
    - [Cybersecurity Podcasts](#cybersecurity-podcasts)
    - [Reverse Engineering](#reverse-engineering)
    - [IT Certification](#it-certifications)
    - [Capture the Flags (CTFs)](#capture-the-flags-ctfs)

- [Mathematics](#mathematics)
- [Others](#others)
- [Comedy/Entertainment](#comedyentertainment)
- [Favorites and Iconic People](#favorites)

![CS Map](src/cs_map.png)
# Overview of the purpose and motivation
- Computer Science is gigigantic. It covers every aspect of computing, both theoretical and practical. It can almost feel as if you are endlessly learning the latest state-of-the-art technologies and tech stacks. After talking with several students on "how to get started with X", whether X is Web Development or just how to begin programming, I wanted to provide resources I accumulated over my time at Chapman in an effort to pass down some knowledge and awareness of FREE learning materials. 

- This can stem from resources that help aid with side-projects, supplemental material for coursework, dialogue of my journey and how I utilize these materials, or just what I follow on a day-to-day basis to stay caught up on the latest tech (twitter accounts, youtubers, podcast, news media). 

- Also DISCLAIMER - Since Computer Science is a huge field, I only cover certain categories that I feel comfortable spreading resources. Not every topic in Computer Science will be listed.

- If you would like to add anything, feel free to message me or submit a pull request. I'm making this open-source so feel free to contribute and provide any helpful resources to your fellow peers!



## Valuable Resources
- #### These are resources I believe is a good investment to either checkout or learn
    - [Github Education](https://education.github.com/)
        - Github education hands out A TON of free resources to students. Please do yourself a favor and take advantage of them. Most of the resources offered are not used in a classroom setting (such as free domain to website, how to get started with X (web dev, mobile application dev, data science/machine learning...)). You can read about all they offer here: [https://education.github.com/pack/offers](https://education.github.com/pack/offers). Amazing resource if you want to do side-projects.

    - Debuggers
        - Specifically, gdb debugger helped me out in pointing me in the right direction when running into segmentation faults in C/C++. But in general, just learning how to use VScode's debugger will save a lot of time. It's suprisingly simple and I feel like it should be emphasized more at university.

    - [AWS](https://aws.amazon.com/)
        - Explore the domain of cloud-computing. AWS offers a 12 month free tier for students

    - Hackathons
        - [MLH (Major League Hacking)](https://mlh.io/seasons/2024/events): The main global hackathon community. If you are looking to participate in a hackathon, look no further. 
        - [Devpost](https://devpost.com/) is also great! It's what most hackathons use for project submissions.

    - [Git](https://www.youtube.com/watch?v=8JJ101D3knE)
        - Understanding how to perform the fundamental commands is fine and will get you through university. But understanding how to work around the more practical "scary" scenarios of using git is important and will be worth your time. This includes creating/merging your branch (when conflicts emerge), git reset, git stash, git rebase, creating a pull request...
            - Most of the time in university you will be working in small projects, either alone or with a small team. This makes it tempting to just use a single branch (typically main). However, when working on a open-source project or working in industry, there will be A LOT more people on board in the software development process. I guarantee that they will be working with more than one branch (if not, then run). For this reason, understanding how it all works is a good investment.

    - Free Hosting Services
        - [Vercel](https://vercel.com/pricing)
            - Vercel provides free hosting services. Can be used to host web-applications
        - [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
            - Github Pages also provides free hosting services to static webpages. The URL of the webpage is typically {yourusername.github.io}. Github pages is perfect if you want to build a portfolio website.

## Software Engineering
### Web Development
#### My Web Development Journey (during university)
- Prior to entering my freshman year (summer), I was learning HTML and CSS. The motivation was to help build a website for a family relative's restaurant. This was also the time where I had no coding experience, went in to university undeclared, and thought coding in HTML was what being in Computer Science is all about. 
- Prior to my sophomore year (summer), this is when I attended my first couple virtual hackathons and self-learned Flask, and what APIs are, and how to integrate them into my Flask application.
- Prior to junior year (summer), I realized that if I wanted to do a deep dive into web development, learning javascript is inevitable (no more Flask in python :/ ). So I partitioned part of my summer learning the syntax of javascript (1-2 weeks), and then spent some time learning ReactJS and how to integrate it into a full stack application.

- Junior year to current last semester of senior year (applying full stack development to different ongoing projects)
    - Here is when I practiced a lot and really getting comfortable with the full stack development workflow. Throughout the school year, participating in several hackathons gave me lots of experience in full stack development. It was hands on practice that you don't get a chance to do inside a classroom setting! I worked on several side-projects I've been inspired to work on, and also helped friends build out a website portfolio which exposed me to more advanced web development concepts. 

- Sidenote on self-learning (goes for anything when watching a youtube tutorial): {Tutorial Hell}
    - After you finish a programming tutorial that's an hour long on youtube, ask yourself, do you really know how to apply what you just learned? Can you now go out on your own and build a project from scratch? The answer is most likely, no.
        - This is called Tutorial Hell. This [Medium](https://www.linkedin.com/pulse/how-escape-tutorial-hell-ikechukwu-vincent) article does a great job explaining what Tutorial Hell is. But essentially, when you watch programming tutorials without applying it to your own application, you get stuck. Remember, learning programming comes from trial and error and spending those long hours debugging, not by watching youtube tutorials. Youtube tutorials is a great way to get started and learning the concepts/syntax along the way, but it's when you do the APPLYING the concepts to real practice where you finally escape the "Tutorial Hell".  


#### Web Development Resources
- [Freecodecamp](https://www.youtube.com/c/Freecodecamp)
    - [Learn Programming – Free Software Development Courses for Beginners](https://www.freecodecamp.org/news/learn-programming-free-software-development-courses-for-beginners/)
- [TraversyMedia](https://www.youtube.com/@TraversyMedia)
    - Provides several web development tutorials. Prior to freshman year, I used his videos to learn how to build a static HTML and CSS webpage. Later revisited his videos when learning the basics of javascript and transitioning into full stack development my junior year.
- [WebDevSimplified](https://www.youtube.com/@WebDevSimplified)
    - Youtuber who creates web development tutorials. I personally used his videos to learn how to use ReactJS.
- [Lama Dev](https://www.youtube.com/@LamaDev)
    - Lama Dev creates several full stack development tutorials. I used his videos to build my first full stack web application using MongoDB, ExpressJS, ReactJS, and NodeJS (AKA, the MERN stack).

### Data Structures and Algorithms (DSA)
- [CSDojo](https://www.youtube.com/@CSDojo)
    - Offers several videos on Computer Science Concepts. Personally, I use his videos to review DSA.
- [Abdul Bari](https://www.youtube.com/@abdul_bari)
    - Amazing resource for reviewing DSA concepts.

### Other Software Engineering Resources
- [TechWithTim](https://www.youtube.com/@TechWithTim) 
    - I used a lot of his videos freshman and sophomore year to get inspiration for programming side-project ideas. This is also how I got started with a lot of my beginner projects. His programming language preference is Python, so a lot of his videos will be Python-oriented. I've self-learned web scraping, API development using Django and Flask, and other beginner friendly projects from his videos.

- [Agile](https://asana.com/resources/agile-methodology)

### Software Engineer Interview Prep
- [Cracking the Coding Interview 6th Edition](https://github.com/Avinash987/Coding/blob/master/Cracking-the-Coding-Interview-6th-Edition-189-Programming-Questions-and-Solutions.pdf)
    - Basically the equivalent of the blue SAT book, but for technical interviews for software engineering.
- [Neetcode](https://neetcode.io/)
    - An extensive leetcode list that you will prepare you for technical interviews. Neetcode contains the Blind 75 (most popular list of DSA problems) as well as the NeetCode 150 (more problems if you need more practice in a specific area). He also has a youtube that goes over the solutions to the leetcode problems.
- [Knock 'em dead](https://www.amazon.com/Knock-Dead-Job-Interview-Interviews/dp/1440536791)
    - Very useful when preparing for behavioral interviews

## Data Science
- Research News
    - [MIT News](https://news.mit.edu/topic/machine-learning)
    - [r/MachineLearning](https://www.reddit.com/r/MachineLearning/)

- Learning Resources
    - [StatQuest](https://www.youtube.com/@statquest)
    - [Yannic Kilcher](https://www.youtube.com/@YannicKilcher)
        - Creates ML videos on research papers, issues of AI
    - [3Blue1Brown](https://www.youtube.com/@3blue1brown)

- Getting started with Machine Learning
    - [Machine Learning Specialization](https://coursera.org/specializations/machine-learning-introduction) 
        - Andrew Ng is a globally recognized leader in AI. This course is great if you want to get started with ML. It's beginner friendly and is regarded one of the best.
    - [CPSC392 Playlist](https://www.youtube.com/playlist?list=PLmxpwhh4FDm5zuA_63jV6iiz5wrg76UHV)
        - This playlist introduces you to the foundational concepts of data science. Videos are created by one of our Chapman professors, Dr. Chelsea Parlett. If you aren't taking the class but still want to learn data science, I would recommend watching the videos to understand the concepts but also do some practice on your own (this means physically typing out code).
    - [CPSC393 Playlist](https://www.youtube.com/playlist?list=PLmxpwhh4FDm5MkEi6m1Tm9vu-MEyiIR5f)
        - This playlist is also made by Dr. Chelsea Parlett and introduces Deep Learning concepts.

- Datasets
    - [Kaggle](https://www.kaggle.com/)
        - One of my favorite places to look for datasets. They also hold kaggle competitions which are widely known in ML.
    - [Hugging Face](https://huggingface.co/)
        - Free ML models you can install and run on your local machine. I recently played around with stable diffusion.
    - [Google Dataset Search](https://datasetsearch.research.google.com/)
    - [Data.gov](https://data.gov/)

## Cybersecurity
### Cybersecurity Youtubers
- [John Hammond](https://www.youtube.com/@_JohnHammond)
    - John Hammond is one of my favorite cybersecurity youtubers. He offers valuable videos related to hacking, covering digital forensics, malware analysis, and just what a SOC analyst does. He covers some penetration testing (such as bruteforcing domain passwords). 
- [NetworkChuck](https://www.youtube.com/@NetworkChuck)
    - NetworkChuck content relates to hacking-related job paths, setting up environments, networking concepts... 
- [David Bombal](https://www.youtube.com/@davidbombal)
    - David Bombal gives a lot of beginner friendly tutorials in the realm of IT. He also invites a couple of guests to chat in a podcast-style setting. 
- [Loi Lang Yang](https://www.youtube.com/LoiLiangYang)
    - Informative videos on pen-testing
- [LiveOverflow](https://www.youtube.com/LiveOverflow)
    - Video tutorials about CTFs, hacking, and finding bugs.

### Cybersecurity News
Where I get my cybersecurity news from.
- Twitter (or "X")
    - I've asked several cybersecurity experts (CISO of Fox, former CEO of Target, North Dakota Government Intel team...) where they get their cybersecurity news from. And suprisingly, they get their threat intelligence from twitter. I personally created a separate twitter account aside from my personal just to keep up with cybersecurity. Here's a couple that I follow

    - https://twitter.com/uuallan
    - https://twitter.com/cyb3rops
    - https://twitter.com/vxunderground
    - https://twitter.com/philvenables
    - https://twitter.com/BleepinComputer
    - https://twitter.com/stanfordio
    - https://twitter.com/TheRecord_Media
    - https://twitter.com/TheHackersNews
    - https://twitter.com/threatpost
    - https://twitter.com/NCCsecurityUS
    - https://twitter.com/Sans_isc
    - https://twitter.com/HackRead
    - https://twitter.com/USCERT_gov
    - https://twitter.com/bishopfox
    - https://twitter.com/maddiestone
    - Also just look up the #cybersecurity and see what's trending.

- [Y Combinator](https://news.ycombinator.com/)

### Cybersecurity Podcasts
- [Darknet Diaries](https://darknetdiaries.com/episode/)
- [Cyberwire](https://thecyberwire.com/)


### Reverse Engineering
- [Ghidra](https://ghidra-sre.org/)
    - Open source reverse engineering tool developed by the NSA
- [crackmes.one](https://crackmes.one/)
    - CTF problems if you want to practice

### IT Certifications:
- [IT Certification Roadmap](https://cyber-center.org/wp-content/uploads/2022/02/04687-it-certification-roadmap-nov2020-24x36-onepage-1.pdf)
    - Sidenote: There's a long-standing debate within the IT space regarding whether a IT certification is needed to jump start a career. I wanted to put this certification roadmap just as a way to display the many certifications out there, not as an actual roadmap guide.

### Capture The Flags (CTFs):
- [National Cyber League](https://nationalcyberleague.org/)
    - Most popular CTF for high school/university.
- [picoCTF](https://picoctf.org/)
- [LA CTF](https://lac.tf/)

## Mathematics
- [Professor Leonard](https://www.youtube.com/@ProfessorLeonard)
    - Youtube professor that explains Calculus 1, 2, and 3 VERY VERY CLEARLY! I highly recommend watching Professor Leonard's videos whenever you get stuck understanding math concepts. I used his videos very extensively back when I took Calculus 2 and 3, and it was game-changing. Videos are a bit long though, as it is very much in a classroom lecture setting, so watch as supplementary material or if you have time.


## Comedy/Entertainment
- [Mark Rober](https://www.youtube.com/@MarkRober)
    - Former NASA Engineer who creates very cool engineering videos.
- [Michael Reeves](https://www.youtube.com/@MichaelReeves)
    - Does some interesting engineering/robotics projects... The more comedic version of Mark Rober. My personal favorite youtuber.
- [Joma Oppa](https://www.youtube.com/@jomaoppa/)
    - Comedy skits surrounding software engineering.
- [Fireship](https://www.youtube.com/@Fireship)
    - Tech news in a fast but comedic manner. Best known for his "___ in 100 seconds" videos.

### Favorites
- Donald Knuth
    - Most famous for the book "The Art of Computer Programming" and known as the Father of algorithm analysis.
- Andrew Ng
    - One of the current leaders in AI. Also known for his Machine Learning courses on Coursera.

## Others
- [Domain of Science](https://www.youtube.com/@domainofscience)
    - Interesting maps created for different domains
- [Zach Star](https://www.youtube.com/@zachstar)
- [Computerphile](https://www.youtube.com/@Computerphile)
    - Interesting videos on computer theory, algorithms, cybersecurity...
- [Veritasium](https://www.youtube.com/@veritasium)
- [Huberman Podcast](https://www.hubermanlab.com/podcast)
    - Talks about health and the science of everyday life. Not really Computer Science related but added since it's one of my favorites to listen to while on a walk or driving at the moment.