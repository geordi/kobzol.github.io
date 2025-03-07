---
layout: "post"
title: "PhD postmortem"
date: "2024-11-12 23:00:00 +0100"
categories: research
---

I haven't been blogging for the past ~eight months, because I was quite busy finishing my [PhD 
thesis](https://kobzol.github.io/phd). I have finally submitted it by the end of August, and 
as of today, I have also succesfully defended it, which marks the end of my six (!)
years[^study-duration] long PhD study in the area of High-Performance Computing and Computer Science.

[^study-duration]: My PhD study officially began on 30th August 2018, so the total study duration was in fact even longer than six years.

I'm writing this blog post as a sort of "postmortem", to gather and record my thoughts on my PhD
study while they are still relatively fresh. I'm doing it mostly for my own future recollection, but
I figured that since I'm writing it down, I might as well also publish it as a blog post,
because why not. The first part is a high-level summary of my PhD, while
the [second part](#my-phd-study-over-the-years) is more of a historical diary detailing what I have
been doing over all these years.

I don't know if this will be useful to anyone (else but me). Perhaps if you're wondering whether you
should do a PhD, this post could serve as a random datapoint for inspiration on what to do (or rather mostly on what *not* to do :grin:).

## Why did I start a PhD?
Kind of an obvious question that I was asked a lot by my friends & family. I'm still not sure if I
know the exact answer, but what served as my original motivation (and what I have been telling
everyone) is that I wanted to try teaching students. During my pregraduate and graduate studies, I
was spending *a lot* of time tutoring and helping my classmates[^classmate-help-count]. It was
something that I both enjoyed very much and that I also felt was improving my skills, because I had to
understand topics well enough to be able to explain them to someone else. Teaching at a university 
felt like a natural next step.

[^classmate-help-count]: I estimate that I gave advice with something related to computer 
    science to 200+ students across several years of my (pre-PhD) studies, and many more after 
    I started teaching officially. Once I even did an informal tutoring session for 60+ students in 
    a lecture classroom, lol. Good times.

And indeed, after I started my PhD, teaching others became a passion for me. During these six years,
I wrote a 200+ page interactive [web book](https://mrlvsb.github.io/upr-skripta) for an 
introductory *C* programming course, prepared hundreds of homework and test assignments, helped 
create or modernize *C*, Python, *C++* and machine learning courses, contributed to and propagated 
the usage of an online [code submission tool](https://github.com/mrlvsb/kelvin) to facilitate code reviews of student submissions, spent countless
hours on Matrix and Discord helping students with their programming assignments[^wife-quote] and 
even designed a completely new subject (it's about [Rust](https://github.com/Kobzol/rust-course-fei), of course :smile:).
In general, I was trying to motivate students 
to improve their skills by practicing coding on lots and lots and lots of programming exercises 
that I have prepared for them, and also to think about the way they design their programs and 
consider their trade-offs. I found this very rewarding and enjoyable, and learned a lot during 
the process.

[^wife-quote]: My wife sometimes jokes that I'm married to both her and my students… :sweat_smile:.

My second main motivation was an opportunity to work with a group of awesome people at the supercomputing center where I have enrolled for a PhD. I have known most of these people already from my bachelor and master studies, and I wanted to work with them and learn from them. This also turned out great, as our small research group was a wonderful and fun place to work (while it lasted).

## Why did it take me six years?

To clarify, a PhD study at my university should ideally last 3-4 years, although sometimes (such as in my case) it can also be almost twice as long[^western-university]. So why did I study for so long?
Well, you might have noticed that my motivations described above did not at all mention aspects like doing research, reading papers, publishing… in other words, the things that a PhD student should actually be doing. It's not that I wasn't interested in doing research, but my study was affected by various circumstances that were not helping (or motivating) me to finish it sooner:

[^western-university]: Our PhD system is quite different from systems used e.g. at some "western" universities, where there's often a hard deadline at the three-year mark.

- Perhaps one of the most straightforward reasons why I was not focusing on my PhD for quite a long time was that I had no idea what my PhD is about. My original topic was something like "HPC & machine learning", which is as generic and broad as a topic can be; I did not really know what I should research. In the end, I kind of "went with the flow" and worked on whatever my colleagues were doing at the time, and eventually I synthesized a thesis topic that encompassed the most important publications that I have contributed to. Not having a clear goal (nor a clear deadline; see below) was probably the main cause for my lack of motivation to grind on my PhD thesis. 
- For most of my PhD, I had a full-time job at an HPC center. While this work was (more or less) related to my PhD, it was still work, which was often taking my attention away from progressing with my thesis.
- As was already mentioned, I spent *a lot* of time teaching, preparing materials for students and tutoring students. I loved every second of it and I certainly don't regret it in any way, but I also realize that effort spent on teaching activities did not contribute much to my PhD. Although I was telling myself that if I want to continue teaching, I will have to finish my PhD one day[^teaching-contract] :) By the way, unlike many (most?) PhD students, I had no obligation to teach, because my PhD was under a research institute (the HPC center) and not under a faculty. So all my teaching activities were strictly voluntary.
- I had no deadline. I'm pretty sure that this was the primary bottleneck that limited my 
  motivation. I knew that I would need to finish my thesis at some point, but until there was a 
  clear date (which was only given to me ~10 months before I submitted the thesis), I could not 
  find the motivation to fully focus on my thesis. And even then, I submitted my thesis only 4 
  days before the deadline :grimacing:. In fact, the main reason why I was given a deadline in 
  the first place was that the study programme that I was enrolled in was supposed to be shut 
  down by the end of 2024. So if I didn't defend my thesis in that year, my study would be 
  essentially over.
- Apart from teaching at my university and working a full-time job, I also did many other activities. I spent a lot of time working on [open-source](https://github.com/intellij-rust/intellij-rust/pulls?q=is%3Amerged+is%3Apr+author%3AKobzol) [projects](https://github.com/rust-lang/rust/pulls?q=is%3Amerged+is%3Apr+author%3AKobzol), [became](https://www.rust-lang.org/governance/teams/compiler#team-wg-compiler-performance) a [member](https://www.rust-lang.org/governance/teams/infra) [of](https://www.rust-lang.org/governance/teams/infra#team-bootstrap) [the](https://www.rust-lang.org/governance/teams/compiler#team-wg-parallel-rustc) [Rust](https://www.rust-lang.org/governance/teams/compiler#team-wg-binary-size) [Project](https://github.com/rust-lang/team/blob/master/teams/community-survey.toml), did some programming contract work, prepared two AI exhibitions at a science museum, started a small machine learning company with my colleagues/friends, acted as a [PyLadies](https://pyladies.cz/) coach, organized and [participated](https://github.com/kobzol/sigmod-2019) in several programming contests, joined an effort to implement a national Covid contact tracking mobile app, helped organize various events and meetups, gave a dozen of talks at conferences and meetups and probably also did a bunch of other things that I already forgot. And that's not counting my personal/family life and non-programming hobbies, such as playing time-consuming computer games[^wow].

  I don't know where exactly it originates from, but my colleague likes to quote something like 
  this: "For every hour you spend on other activities (such as work), you should spend two hours 
  on your PhD". After remembering all the (non-PhD) things that I did during these six years, I 
  am actually amazed that I managed to complete my PhD at all…
- Last but not least, I was generally not super motivated to do research. While there were a few periods of time when I was genuinely excited about studying the state-of-the-art in a certain area, reading and writing papers and performing experiments, they were always quite brief and were usually followed by months of procrastination.

    I also became slightly disillusioned about research in general quite early in my academic career, due to somewhat ironic circumstances. In the first year of my study, I did a six months internship at the [SPCL](https://spcl.ethz.ch/) lab at ETH, Zurich, one of the most prestigious universities in the world; there I saw how research is done at the [best](https://csrankings.org/#/index?hpc&world) HPC lab in the world. This was a totally awesome experience, through which I met many wonderful people and also were able to contribute to [several][SISA] [high-profile][SMI] [articles][SPIN] [published][RISCV] at the most prestigious HPC/CS conferences and journals. However, it also made me believe that we will probably never be able to perform research on this level within our small group, simply because we lack the appropriate resources. This actually made me demotivated after I returned back from the internship; I'm a very competitive person and when I felt like we couldn't be the best in what we're doing, I thought "why bother at all". In hindsight, I view this a bit differently. Over the years, we were able to do really cool stuff with a small group of dedicated people, and I myself could do so much more, if I just spent more (than the bare minimum of) effort on my PhD. But that was never a priority for me, as I lacked the necessary ambition and motivation.

    Furthermore, my colleagues did not push research activities very much, because some of them already had their PhD title, while others did not really care that much about finishing it. That's not a problem on its own, but when it was combined with my lack of motivation and effort, it led to my PhD progress being *very* slow.

*[HPC]: High-Performance Computing
*[CS]: Computer Science
*[SPCL]: Scalable Parallel Computing Lab

[SISA]: https://dl.acm.org/doi/10.1145/3466752.3480133
[SMI]: https://dl.acm.org/doi/10.1145/3295500.3356201
[SPIN]: https://www.researchgate.net/publication/337110339_Network-accelerated_non-contiguous_memory_transfers
[RISCV]: https://ieeexplore.ieee.org/document/9499874

[^teaching-contract]: Which was not even true, as I eventually found out. It is possible to teach at our university as a contractor without a PhD.

[^wow]: Yes, I'm looking at you, World of Warcraft.

After recollecting these "circumstances", I realize that I was quite lucky that I was even able to finish my PhD, because my priorities during these six years were usually focused somewhere else. I also saw that every road to a PhD is different, and even for two students enrolled in the same university, study subject, even the same lab, it can look wildly different.

To expand on that a bit, after my PhD experience, I would say that the most accurate predictor of 
whether a PhD (student) will succeed or fail is not their initial skill or dedication nor the 
actual topic of their thesis, but rather the environment in which the PhD student operates. Working 
with(in) a group of people that research similar topics, collaborate with you on publications 
and provide support and guidance makes all the difference. Just the feeling that you're not 
alone for what can often feel like an insurmountable amount of work can be a gamechanger. On the 
other hand, doing a PhD on your own, without any such support, can be brutal. There are 
definitely people that have managed to successfully finish a PhD in such a solitary environment; 
I have a lot of respect for them. And of course, not only the work/study environment is 
important; personal and family environment is also a big factor.

To be clear, I *have* experienced the benefits of such a supportive environment, both in work 
and in my family, otherwise I would never be able to finish my PhD. The main reason why my PhD 
took so long was simply a lack of motivation and general laziness on my part.

## What was my PhD about?

That's probably the least interesting part of this blog post, but I felt like it would not be complete without mentioning it. So, to put it short:

1. Scientists use supercomputers (HPC clusters) to perform expensive simulations and experiments.
2. These experiments are computed with complex distributed applications, often consisting of many different programs and scripts.
3. Such applications are commonly implemented using task-based programming models and task graphs.
4. Executing task graphs on supercomputers can be quite annoying and sometimes not as efficient as it could be. This is caused by various reasons, primarily by the fact that supercomputers were historically designed with quite different programming models (such as MPI) in mind[^sota-chapter].
5. We can design approaches for making task graph execution on supercomputers more ergonomic and more efficient.

[^sota-chapter]: If you want to find out more, feel free to read
    [Chapter 4](https://kobzol.github.io/phd/#pf25) of my thesis :)

Step 4 was the motivating issue for my thesis and step 5 is essentially what my thesis is primarily about.
The topic of my thesis is `Ergonomics and efficiency of workflows on HPC clusters` and one of 
its main outputs is the [HyperQueue](https://github.com/it4innovations/hyperqueue)[^in-rust] 
task runtime, which is the result of a team effort of our group. HyperQueue was created to help 
users execute their task graphs in a way that is very straightforward, but also efficient at the 
same time. It has been adopted by tens of different researchers across Europe, it is designated as 
one of the primary ways for executing task graphs in several European HPC centers, and it has also 
been leveraged in various research projects. For example, it is being used to [analyze data](https://cds.cern.ch/record/2837871/files/ATL-SOFT-SLIDE-2022-550.pdf) from 
the Large Hadron Collider in CERN, and it was also used to execute one of the largest 
molecular dynamics simulation [campaigns](https://ec.europa.eu/research/participants/documents/downloadPublic?documentIds=080166e50e15aa6d&appId=PPGMS) ever performed. I consider that to be a success and I look forward to developing HyperQueue in the future, in order to make the lives of scientists that want to leverage HPC resources even easier.

[^in-rust]: Implemented in Rust, thanks for asking.

## Was it worth it?

Well, there were certainly pros and cons, as with everything.

Regarding the benefits, enrolling for a PhD presented me with several opportunities, such as teaching students at a university, collaborating with great people, working with supercomputers and experiencing an internship abroad. One can always wonder about "opportunity cost" -- even if I did something that I liked, maybe I could do something even better if I was in a different situation? However, I am not worried about this very much; as I described above, I actually spent *a lot* of time doing non-PhD things that I enjoyed very much during these six years, so I don't feel like I have missed out much.

Doing a PhD leveled up my perseverance and also helped me realize which kinds of people I want to work and interact with (and which kinds of people I want to avoid). In particular, I learned to appreciate a certain character trait that I affectionately call "no bullshit". People with this trait act and talk in an honest way, can constructively criticize not only the work of others, but also their own work, when they think that it should be improved, are not afraid to admit their own mistakes and generally act in good faith. I met several people that have this trait, both during my internship and in my lab; I always enjoyed working with them very much, and they have also inspired me to try to act in the same vein. Sadly, I also met various people that represented almost the exact opposite of the described behavior. Interacting with them made me feel disenchanted, sometimes outright mad, and I thus tried to avoid these interactions as much as possible.

As for the cons, I think that the main negative aspect of my PhD study was (unsurprisingly) stress. I cannot say that I felt it uniformly throughout the whole time of my study, but stress is tricky; it can affect you even if you do not realize it. I have been certainly feeling it much more during the last year of my study, when I finally got a deadline and knew that I have to (or at least should) finally finish my thesis. But I think that in reality, it was there the whole time, hanging above my head like a [sword of Damocles](https://en.wikipedia.org/wiki/Damocles), even when I wasn't explicitly noting its presence.

It is a bit funny that I was stressed out over finishing my PhD, because there was not really any objective reason why I *had* to finish it; I knew that I could find work that pays well and that I enjoy even without the title, and I wasn't planning to continue with an academic career anyway. I think that in my case, it was the good ol' fear of being perceived as a failure; I did not really care if I fail or not, but I was internally afraid of "what would others think" if I failed. It is incredibly stupid, but it's difficult to change how one's mind works; I had a successful track of record in my studies so far and I felt like others expected me to succeed. 

Now that I have finished my PhD, I cannot say that I would feel much relief though, which is a bit disappointing.
I sort of expected a big weight being taken off my mind, but it… sort of feels the same? Nevertheless, at least it's finally over, and I don't need to think about it in the future anymore, which is nice.

Taking everything together, I think that it was worth it for me to do a PhD. On the other hand, I don't think that I would recommend it to others, particularly if they do not have a clear and strong motivation for doing a PhD, same as I did not.

## What's next?

I do not plan to continue in an academic career in the near future. I still work on HyperQueue at the HPC center, and I wouldn't mind performing some experiments or writing a publication from time to time, but it is definitely not something that I would like to prioritize. I want to continue teaching university students, as that is something that I enjoy very much. And regarding work, I would like to continue contributing to open-source, which I find truly fulfilling (and I found funding for it, which is truly a dream come true, while it lasts).

## My PhD study over the years

This is the "diary" part of my PhD recollection. I'm writing it for myself to remember what I have been doing over the six years, and also to help me understand what the hell has happened :)

### First year (2018 - 2019)

At the beginning of my PhD, I didn't really have any clear idea on what to research, so I was mostly focusing on other things. I spent a lot of time working on an idea of my colleague called [Snailwatch](https://snailwatch.readthedocs.io/en/latest/), a benchmarking service that would monitor the performance of a project over time (and git commits). I think that at the time, it was a pretty cool idea. However, we did not really know how to propagate it among users, and also back then, the HPC world was barely prepared for correctness testing in CI, much less for *performance* testing in CI. In hindsight, it was more of a project for a company than for a research institute, but we had no interest in starting a company, so we gradually abandoned the project. It is a bit funny to see that only recently, after 3-4 years, the first companies that offer something like this as a general service (such as [Bencher](https://bencher.dev/) or [Codspeed](https://codspeed.io/)), have started to appear. And funnily enough, I started my open-source contributions to Rust by maintaining the [Rust benchmark suite](https://github.com/rust-lang/rustc-perf), which does something very similar in the context of the Rust compiler. So even though this had absolutely no overlap with my PhD, continuous performance benchmarking is still something that I deal with very frequently.

*[CI]: Continuous Integration

As already noted, I did not really know what my PhD should be about, so I started collaborating on research performed by my colleagues. At that time, the main research area of my group was creating tools for scheduling and executing programs (tasks) on distributed clusters, primarily supercomputers. The start of my PhD coincided with the start of a new project called [ESTEE](https://github.com/it4innovations/estee), a Python simulator for experimenting with task schedulers, so I started helping out with that. We implemented the tool, performed a large-scale study of various scheduling algorithms, and wrote a publication about it, which took… *checks notes* four years to publish. We tried once in 2019 and then three more times in 2020, at which point my colleagues simply stopped caring. Luckily, I somehow found the motivation to try for a fifth time (probably because of the [*sunk cost fallacy*](https://thedecisionlab.com/biases/the-sunk-cost-fallacy)) and have finally [succeeded](https://link.springer.com/article/10.1007/s11227-022-04438-y) in 2022. This paper was not exactly a ground-breaking piece of research, but I also don't think that it was completely bad, so the experience of failing to get it published for four years was pretty harrowing. That experience has followed me throughout most of my PhD study, and together with some other experiences (both mine and of my colleagues), it made me somewhat [doubt](https://www.experimental-history.com/p/the-rise-and-fall-of-peer-review) the peer review process. But in the end, I was primarily glad that we managed to finally get it published after all that time.

Apart from Snailwatch and Estee, I was working on other work stuff, especially various large projects funded by the European Union. I could write a whole blog post (probably multiple ones) about these, but that's a different story. One fun work assignment that we have received soon after I started working at the HPC center was to fix unstabilities in a distributed system designed for simulating the movement of (tens of thousands of) cars within a virtual city. After examining the system, we quickly realized that it is beyond saving, and we decided to rewrite it from scratch. We had approximately three weeks for that, so as I said… *fun*. After seeing the many issues of the previous implementation of this system, written in a combination of *C++* and Python, I decided to rewrite the service in Rust, which was my first experience with using the language for a "production" use-case. And it was great! Even back then, when async Rust was in its infancy and `async/await` was not yet stabilized, I felt very productive with the language, and fell in love with it. Apart from Rust, I also leveraged the [ZeroMQ](https://zeromq.org/) message broker for distributed messaging, which was quite cool. I remember reading the whole ZeroMQ manual from start to end and imagining all the things that could be built upon these foundational network primitives. And these two technologies have definitely delivered; the port was completed in a few weeks, it was stable, scaled to multiple nodes and had relatively good performance. And then, it was almost immediately abandoned, but that's not super important for this story.

In terms of teaching, I started lecturing a Python programming course. It was a pretty surreal experience, suddenly being at the opposite side of the classroom, explaining something to people that sometimes looked older than me :laughing: But I was really enjoying it and I still enjoy it to this day.

Right at the start of my PhD, I was told that I will have to go for an internship abroad at the start of the next year (2019). This was a bit of a shock to me, but I figured out that it's something that belongs to a (PhD) study, and that I should embrace this fact, rather than fight it. I was lucky to have the opportunity to actually choose the specific lab at which I would do the internship. With the help of a colleague and her friend, I got a recommendation for the SPCL lab in Zurich, which is essentially the [best HPC lab](https://csrankings.org/#/index?hpc&world) in the world. I had an interview with them in which I didn't particularly shine in terms of research/math knowledge, but in the end my passion for [performance optimization](https://github.com/Kobzol/hardware-effects) and knowledge of CPU micro-architecture apparently made some impression. In the end, I suppose that SPCL did not have a lot of reasons *not* to accept me; the European Union was paying for the whole internship, so I was a free helping hand at best and an occupied office seat at the worst.

My internship began at the start of 2019, approximately one month before the paper submission deadline of [SuperComputing](https://supercomputing.org/), probably the biggest HPC conference in the world. This was probably the busiest time of the year for the lab; I arrived right at the eve of a big planning meeting that heralded a final sprint of performing experiments, doing research and writing papers for this conference. Originally, I was supposed to help with a single specific project (essentially getting CUDA-like compute kernels onto NICs). However, I'm apparently incapable of working on a single project for a long period of time, because I always feel the need to context switch between different projects. This trait kind of became the bane of my PhD study; guess what's a single project that runs for a long time? A PhD (thesis) :). Therefore, I quickly switched to a breadth-first, rather than depth-first, approach and started working on I think four projects at once. I was mostly helping out with coding and performing experiments, which is something that I was relatively good at, while observing other world-class PhD students and postdocs do the real research :) But in the end, I think that I made meaningful contributions to the papers that I collaborated on, which certainly felt good.

*[NICs]: Network Interface Cards

While I was doing the internship, I was told that I should apply for a research grant that supported prospective students in our region. I did not pay it much attention (as usually, I was told about this a few days before the deadline), and scrambled together a proposal for a research project focused on applying machine learning principles to task scheduling (which was an idea that was originally supposed to be my PhD topic). This would later haunt me a bit, as described later below. For fun, I looked through the grant application from back then and found that I wrote there that "I expect to finish my PhD in 2022" and that "the proposed topic will be highly relevant to my PhD thesis" (spoiler alert: both of these claims turned out to be wrong).

During my internship, I also started contributing to open-source a lot, primarily to the [IntelliJ Rust IDE plugin](https://github.com/intellij-rust/intellij-rust). This was a very rewarding experience and I had a lot of fun with it; I continued working on the plugin for several years, until it eventually became closed-source with the introduction of [RustRover](https://www.jetbrains.com/rust/). Describing my Intellij-Rust contributions was also the original reason why I [started]({% post_url 2020-08-23-contributing-1-nest-use-fix %}) this blog :) And of course, apart from contributing to Rust-related projects, I was also evangelizing Rust and propagating its usage within HPC to anyone who was willing to listen at SPCL :)

I also participated in the [SIGMOD programming contest](https://github.com/kobzol/sigmod-2019) during my internship, for the fifth year in a row. This was a very cool contest for students all over the world, which focused on performance optimizations, an area that was (and still is) fascinating to me. I learned an incredible amount of stuff about making programs faster by participating in this contest over the years. It was also incredibly time-consuming, at least for me; I remember spending at least five or six hours a day for essentially two months in a row, trying to optimize my solution as much as possible. That year, the contest was focused on I/O performance; I remember reading the Linux I/O syscall documentation back and forth multiple times to figure out the best way to move bytes from place A to place B on disk. Same as in 2018, I finished at the second place and was thus invited to attend the SIGMOD conference in Amsterdam, which was quite nice. From the following year, the format of the contest has changed; it focused less on performance optimizations and more on data science, which made me lose interest in the contest. In hindsight, stopping participating in the SIGMOD programming contest was probably a good thing for both my mental health and my PhD progress, otherwise I would continue "losing" two whole months of free time each year.

All things considered, the internship was an awesome experience. Not just because I met wonderful people, gained a lot of experience, improved my research and computer science skills and collaborated on several publications, but also in terms of independence; it was the first time I had to take (at least some) care of myself, without direct support of my family. The final "academic score" was quite successful; we have published four papers, with a few more in the pipeline, and I was also invited to prolong the internship. However, I did not want to stay apart from my girlfriend and my family for a longer time, so I respectfully declined the offer and returned back to my country.

Once I returned back from the internship, I felt kind of bittersweet. As I already mentioned, seeing how "top research" was done, and comparing it to the way we did research at our university, was a bit demotivational. Furthermore, after my first year of PhD, I was the co-author of several articles published at some of the best computer science conferences and journals in the world, something that most PhD students would probably envy me a lot. However, I still had no idea what my PhD should be about, and since the papers I worked on had relatively little in common, I had a suspicion that what was otherwise a great academic success would be essentially useless for my actual PhD thesis (this suspicion was later confirmed).

*[NIC]: Network Interface Controller

### Second year (2019 - 2020)

After the first year and the end of my internship, I still had no clear idea what I should do for my thesis. My topic at the time was something like "HPC & machine learning", which was very broad. We had an idea with my colleagues to try to apply machine learning to task scheduling, by creating a graph neural network (GNN) that could schedule tasks. This was back at a time when graph neural networks were in their infancy, so we had to figure out a lot of things from scratch. My colleague wrote a high-performance implementation of GNNs with multiple node and edge types (for representing heterogeneous task graphs) in TensorFlow. I'm pretty sure that it was beyond (or at least at the level of) state-of-the-art at the time, but as eventually became our tradition, we sort of lost interest in it after a while and it was abandoned, without even writing any publications about it.

However, the research grant that I applied to during my SPCL internship was about the same topic, and it was also pretty much the only idea that I got for my PhD thesis at that time, so I could not abandon it so easily. Nevertheless, I was not successful in reviving this topic on my own and I couldn't find the drive or motivation to continue working on it, so I eventually focused on other research that was happening in our lab. This topic was a bit cursed from the start, for several reasons. One of my colleagues, who was also doing a PhD at the same time, was supposed to focus on a very similar topic, so I wanted to avoid a clash[^gnn-topic] with them. And in general, I was quite skeptical of doing a PhD in the area of machine learning (ML); with the speed of progress that was (and still is) happening in ML, I felt like anything I would work on would be already done by someone else before I would be able to finish my PhD.

[^gnn-topic]: He eventually ditched his PhD study though, so it would not matter in the end.

At the beginning of my second PhD year, we started working on a new project, [RSDS](https://github.com/it4innovations/rsds). It was an attempt to take a popular technology for executing task graphs ([Dask](https://www.dask.org/)), which we already had a lot of experience with, and make an "HPC-optimized" version of it (because Dask was quite slow for certain HPC workloads). We essentially rewrote the Dask server in Rust and tried to optimize it as much as possible. We were able to reach some nice speedups, while making RSDS backwards-compatible with existing Dask programs, which was quite cool. We also spoke with Dask maintainers (and even with some folks from NVIDIA) about the possibility of applying our optimizations to upstream Dask. While it was not really feasible for them to rewrite the server in Rust (d'uh), there were some ideas that eventually made it into Dask and that improved its performance. We wrote a [paper](https://www.computer.org/csdl/proceedings-article/works/2020/104000a001/1q7jxiyDsFW) about RSDS and eventually got it published at a workshop colocated with Supercomputing'20. RSDS was again something that probably had more hope as a startup idea, rather than a research vehicle, but I think that its academic potential was much higher than a single paper at a workshop. Nevertheless, I did not drive any further research based on it, and due to some changes in Dask, it became quite difficult to maintain it, so it also became abandoned. But at least in this case, we were later able to reuse its implementation to bootstrap another project that eventually became the core of my PhD (HyperQueue).

Because I had two publications at [Supercomputing'19](https://sc19.supercomputing.org/index.html)[^supercomputing], I travelled to Denver and visited the conference at the end of 2019. It was a nice experience, especially since I was able to meet my colleagues from SPCL again. 

[^supercomputing]: Apparently, I was the first person from our research institute ever who had a publication in the main SC research track. However, this was of course not primarily my accomplishment, it was due to the publications being co-authored by people from SPCL.

My teaching activities were also continuing. I wrote a large part of an [online book](https://mrlvsb.github.io/upr-skripta/) that was designed to help students bootstrap their knowledge of programming in *C*. I consider the book to be a success, as it is still being updated and used to this day by hundreds of students. I also started teaching a Python course and helped created a completely new *C++* course, where I was mostly just showing students what not to do in *C++* and how to avoid various forms of undefined behaviour :laughing:.

What happened then (in 2020) probably needs no introduction. Covid took the world by storm and my PhD progress essentially stopped, apart from work on RSDS, which we were finishing at that time. During the first "Covid spring", I was locked up in a flat into which we have just moved in with my girlfiend. The flat was freshly reconstructed and therefore quite barebones; we essentially only had a desk, a chair and a bed. I was (remotely) studying a course about graph theory at that time; I remember sitting at my desk in an otherwise empty apartment for hours on end, scribbling notes on a piece of paper and trying to figure out how to design proofs about various graph properties. This taught me a lot about designing mathematical proofs, which I ended up using at least a little bit in my thesis after all. Apart from designing proofs, I also took part in a national-wide effort to implement applications that were supposed to help stop the spread of Covid. In the end, they did not have a lot of effect, but we could not have known that at the time, and doing something felt better than doing nothing.

Covid has introduced the concept of home-office, which was even more relevant for me personally, because the flat that I moved into was in a different city than my research institute (approximately one-hour drive away). This meant that I was no longer regularly meeting my colleagues (almost) every day and I was no longer sharing ideas about what things we could research and work on. Therefore, my already slow PhD progress pretty much grinded to a halt.

At the same time, our group partially refocused from working on distributed systems and task scheduling into becoming a deep learning workshop, partially because it was quite a hot (and still relatively new) topic back at that time and also because we were one of the few people at our research institute that were able to use it to solve real problems. I learned a lot about machine learning during this time, and worked on some interesting projects[^embedded-ai], but this work also had no resemblance to anything that would help me progress with my PhD.

[^embedded-ai]: For example, how to get a neural network running at 60+ FPS on a small embedded chip attached to a robotic device.

### Third year (2020 - 2021)

I don't actually remember much about the "Covid years" or what exactly I was doing regarding my research at that time. We were repeatedly trying (and failing) to publish the ESTEE paper and otherwise spent time working on various machine learning projects. I still had no idea what is my PhD about. However, we have started yet another task scheduling project called [HyperQueue](https://github.com/It4innovations/hyperqueue), which eventually became the backbone of my PhD thesis (even though I didn't know that at the time).

My teaching activities were moved online to remote video calls. It was quite weird talking to a monitor for three hours straight and not seeing the faces of my students, but it was better than nothing.

In 2021, I also started contributing to the [Rust compiler](https://github.com/rust-lang/rust) and its [benchmark suite](https://github.com/rust-lang/rustc-perf). This became a passion for me; I eventually became a member of several teams of the Rust Project. Yet, it was another thing that was eating away free time that I was supposed to spend on doing PhD research.

### Fourth year (2021 - 2022)

Apart from more teaching and doing projects mostly unrelated to PhD research, I don't actually remember much about this year. We were still working on HyperQueue, which was turning into a very useful tool that was actually being used in production[^production] by a dozen of scientists and researches, which was cool. However, no one from my group seemed to be interested in actually writing any publications based on our work and I (again) lacked the motivation to push it forward myself. Which was a shame, because I think that if I had enough drive, HyperQueue could generate a bunch of interesting papers. Instead, we dedicated our energy into making the software better for its users, which was definitely worthwhile, just not that much in terms of moving my PhD thesis forward.

[^production]: Something that couldn't really been said about the previous tools that we have made.

There was one event that motivated me to make progress though; after four years of studying, I had to submit a PhD thesis proposal and perform the doctoral state exam. I finally got some deadline, so I managed to scramble together a ~20-page [thesis proposal](https://github.com/Kobzol/phd/blob/main/output/proposal.pdf) over the summer of 2022. In my proposal, I (somewhat out of desperation) tried to combine as much of the diverse work and research that I have done so far as possible, in order to come up with a story that would encompass it under a single cohesive narrative.

Apparently, I was relatively successful with that, as my state exam, which happened at the end of 2022, went pretty well; the name of my thesis was changed to "Ergonomics and efficiency of workflows on HPC clusters" and it was approved for finalization, which was supposed to happen approximately by mid-2023. You can guess how that went :)

When writing the proposal, I realized that for me, there is no ~~spoon~~ actual PhD topic, which I have been desperately trying to figure out for several years. My breadth-first approach of working on (too) many projects at once has led me to combining a bunch of research agendas together (and calling that a PhD topic), rather than grinding on one specific area for several years in a row, which was how I was originally envisioning my PhD life.

The approach of my state exam coincided with the end of the research grant that I got for the previous three years. I did not finish my PhD by 2022 nor did I even do a PhD about applying machine learning to task scheduling, as I originally planned in the grant proposal. However, I did a lot of other (semi-relevant) stuff in the meantime that I was able to report as work relevant for the grant, so in the end, all was good.

With two of my colleagues, we started a small company, where we tried to help local businesses leverage machine learning to solve various problems or even build ML-powered products. It did not take much of my time and I was quite excited about it back then, but it was yet another entry in a long list of things that had nothing to do with my PhD. I have started (and often struggled to finish) a lot of such activities over the years, partly because the ability to "say no" to various opportunities was not in my spellbook.

### Fifth year (2022 - 2023)

After defending my thesis proposal, I was kind of pumped-up for working on my thesis. I finally had a topic (or at least a thesis title) that encompassed my previous research (ESTEE and RSDS), and I also had a somewhat clear goal: perform more experiments using HyperQueue. I even started preparing a basic paper about HyperQueue on my own at the start of 2023, with the hope of getting it published and also finishing my thesis by the end of summer of 2023. And then… nothing happened. Suddenly, it was autumn, and I realized that I haven't done almost anything on my thesis since the start of the year and the article also hasn't progressed anywhere. I'm not really sure what has happened. Probably I got complacent, because I felt like I finally made some progress after the state exam. I lost track of the goal, started working on other things and several months just flew by. I suppose that the issue was the lack of a deadline again; after defending my proposal, the date for submitting my thesis was relatively open-ended. I was vaguely aware that I should finish it by mid-2025 at the latest, which felt like very far in the future at the time, so I lost my motivation again.

What didn't help was that our research group essentially started falling apart. Some members left, while others reduced their engagement in our research activities. I was lucky to have their support over all these years, and I was still able to consult many things with them, for which I am very thankful. However, it became clear to me that I will have to handle the rest of my PhD mostly by myself, which felt quite scary.

### Sixth year (2023 - 2024)

At the beginning of my sixth year, I was not making almost any progress, as I was assuming that I still have a lot of time left and I did not feel any outside pressure that would motivate me to restart the work on my PhD. That changed at the very last day of October 2023, when I was suddenly given a notice that I have to submit my thesis by the end of August 2024, because my study programme will be ending by the end of 2024. That was a shock to me; I thought that I still have almost two years to finish my thesis, while in reality I only got ~10 months left until the deadline. Even though this was quite unexpected to me, in a way, I was really glad that I finally had a strict final deadline. I knew that no matter what, whether I make it or not, I won't have to think about my PhD thesis anymore after the summer of 2024. That was sort of a liberating feeling that I was *really* looking forward to.

Having a deadline restarted my motivation again, so I have finally bootstrapped (after five years of study!) a document for my thesis out of my proposal and wrote tens of pages within the span of a few weeks. I also realized that I should ideally get the HyperQueue paper into the review process as soon as possible, so that I could get it published before my thesis submission deadline. While I formally had enough papers published at that time already, I knew that it would be better if I also had a publication related to the research project that was supposed to become the backbone of my thesis. So I returned to the paper and finished it in about two weeks, after not working on it for almost a year…

I wrote a few more thesis chapters at the beginning of 2024, after which I started feeling like I'm mostly done. My naïve plan was that I would be finished with the thesis somewhere around March or April, and then I could stop worrying about it. In hindsight, this was a very bad idea. I should have worked on the thesis continuously, rather than assuming that I'm almost done and keeping the remaining work for "later". Since I started feeling complacent, I started filling my available time for the spring. I helped organize several Rust meetups, attended two conferences and gave around five or six conference/meetup talks within the span of a few months, which took a lot of my free time (I usually spend tens of hours doing research, preparing [slides](https://github.com/spirali/nelsie) and practicing for a [talk](https://github.com/kobzol/talks)). At the same time, I had a very busy time at work, as two large European Union projects were finishing at the same time, which was quite crazy. Oh, and did I mention that I was an advisor to *five* bachelor theses that I had to read and review, in addition to having weekly meeting with my students, all just a few months before my own thesis deadline? :laughing: Luckily, at least I was sane enough to opt out of teaching during that semester. That was a good idea; I think that I would probably experience a mental breakdown otherwise, because of all the stuff that was going on.

Because of all that craziness, I stopped working on the thesis again, since I thought that it is mostly done (spoiler alert: it wasn't), given that I "only" had the final chapter to write (hint hint: it was the most complicated chapter that made up essentially a half of the final thesis in the end). In hindsight, I think that I did all those things during the spring of 2024 because I was simply procrastinating from working on my thesis again.

My complacency was further extended when the [HyperQueue paper](https://www.softxjournal.com/article/S2352-7110(24)00185-7/fulltext) was accepted in June; I felt like I'm essentially all done. However, once I finished the meetup/conference/work spree at the beginning of July, I suddenly realized that there are less than two months left until the deadline and that my thesis is still missing many important pieces.

Fun fact: when someone was asking me how does the work on my PhD thesis progress, I was always patiently explaining to them that writing the actual thesis is the easy part; the hard part is performing research and publishing papers, which I had mostly done by the sixth year of my study (or so I thought). And I probably really believed this claim; I knew that I'm able to dish out large quantities of (reasonably readable) English text in a short timeframe, so I was confident that writing the text won't be that hard. Well, what can I say… I was able to write text quickly, but a PhD thesis is still a PhD thesis (in my case, it had almost two hundred pages). And in my experience, good text is never created on the first try; the only way to improve its quality is to iterate, iterate and iterate again. So while writing hundreds of pages was not that difficult for me, rewriting it about three times almost ended up being the straw that broke the camel's back.

After I realized that I still have a lot of work to do, I panicked a bit, and started working on the thesis non-stop. During the summer of 2024, I designed, implemented and performed tens of experiments, and essentially rewrote half of my thesis several times, while adding almost a hundred more pages to it[^page-count] (with approximately twenty being added in the last two weeks). It was quite wild (and stupid) to perform all that work in the final rush before a deadline, but in the end I managed to massage all that text into something that hopefully resembles a cohesive piece of text. It was kind of fun, but… let's not ever do that again.

[^page-count]: The final page count was `182`, don't ask me why.

On 27. 8. 2024, I finally submitted my thesis. I expected that I would immediately feel immense relief, but I cannot really say that has happened. The stress that I felt during my PhD study often felt inconspicuous; in the same vein, I did not feel a significant change after I finally submitted my thesis. I started feeling some relief after writing this blog post, though :) And also after I finally held the printed thesis in my hand: 

![Photo of my printed PhD thesis](/assets/posts/phd-postmortem/thesis.jpg)

After submitting the thesis, I had a bit of a rest from my PhD; the only thing left to do was to prepare
slides for my PhD defense. The defense itself then went well. I had favourable reviews, and presented a ton of stuff that I have worked on over the years. Combined with HyperQueue's impact in the HPC community, the committee voted in unison to give me the PhD title. Yay! :tada:

## Conclusion

So, that was the story of my PhD. Looking back at it, I think that there was a clear recurring pattern; I worked on something interesting for a while, did some research and experiments, then got complacent, lost motivation and stopped working on my thesis for months or even years on end. This was repeating until I got the final deadline, which finally motivated me to finish the text of the thesis. It seems a bit funny that I apparently did most of the PhD work/research right at its beginning and then right before the end, while the middle was quite… hazy.

People familiar with the PhD process might have noticed that some aspects (and actors) that accompany each PhD study were not mentioned here; this was done mostly in order for the text to remain somewhat anonymous and also because I wanted to avoid mentioning some not-so-positive interactions that I had during my PhD study. However, I think that I got most of the important things across.

I'm very grateful to all of my colleagues and collaborators that have accompanied me during my PhD journey, as I could not have finished the thesis without their help. This is a cliché, of course, but trust me, it's very true. Doing a PhD on your own, without help, would be simply insane. I'm also incredibly grateful to my wife and my family, for being super patient with me during all the time I spent working on this seemingly meaningless piece of text.

My thesis probably won't change the world, and I'm not even currently planning to continue with my academic career[^assistant-professor]. Nevertheless, I think that our work (especially HyperQueue) had a meaningful impact in the real world (moreso than in the academic one), for which I am grateful and I consider it to be a success that was enabled (among various other things) by my PhD efforts.

[^assistant-professor]: Although, assuming that I defend my PhD, I would already satisfy the requirements for being an assistant professor, so… one never knows :)

Anyway, that's it. If you made it this far, thanks for reading, by the way.
