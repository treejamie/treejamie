
## Inception

I still have some of the earliest drawings I made as a child — always some kind of complex pipework systems. Systems have always fascinated me – I love them. As I grew up, that morphed into wanting to be an architect. At 16, I left school to study art, applied maths, and biology at college to make that dream a reality. But two months in, I was given a drum set, and that threw a curveball into my academic trajectory. Out with maths and biology, and in with music technology.


## Drums & Internet

Sometime in the late nineties, I became aware of the internet. The band I was in needed a website, and thanks to my music tech course, computers didn’t feel alien. I started hacking and learning. Seeing my first web page was electric. When I got my hands on [The Perl Cookbook][0] and websites could interact with the world. I felt like a magician. By day, I was technically a professional drummer because we had a record deal. I remember being at a party in Gateshead when John Peel played our latest single on Radio 1. I hadn’t known it was coming and hearing your own band at a party in the late 1990's was surreal. It was a moment of joy and uncertainty — I knew that I'd done what I set out to do as a drummer. But what next?

## ActionScript & PHP

By 2004, I’d self-taught enough to land a job as a “web designer.” I’d completed a BA in Multimedia Design and was skilled in Flash ([ActionScript 2/3 – essentially ES3][1]) and Director (Lingo). PHP was catching on, but that was for “backend” people — I was frontend. Back then, there was no line between work and personal time. For three solid years, I designed in Flash, XHTML, CSS, and JavaScript. Still, I was a designer with trust issues, so I often wrote backend code too — just to be sure it worked. PHP felt dreamy: write code right on the page, have Apache run FastCGI, and off you go. I shudder now, but at the time it was liberating. Days were for building; nights were for books, scripts, and personal projects. We had [CVS][3] instead of git and we transferred everything via FTP (>_<). Drag and drop deployment at its best vintage.

## Django


At d.Construct 2006 in Brighton, I met a guy called James. He’ll never know it, but he changed my life. How? He showed me a [very early Django][2] — and my mind was blown. ORM, templates, testing, auth, and the crown jewel: the admin interface. I stuck with PHP at work (we were using Zend Studio and the Zend Framework), but outside of work, it was all Django. From October 2006 to February 2007, Django consumed me. I was so sure Django was the thing that I quit my first tech job to start a design and dev consultancy with a long-time (and still very good) friend. CVS had turned into Subversion, and FTP had morphed into SFTP — secure drag-and-drop deployment. Magic.

## C&C Design Consultants

From 2007 to 2013, I built over a hundred Django sites — six years of trial by fire. By the end, I felt like I could do anything with it. We'd built intranets, ecommerce websites (_handrolled, not satchmo_) brochure sites and even tackled a couple of failed self startup ideas.  Subversion and SFTP had become primitive CI & CD. A fabfile would run tests and if they passed it would then deploy to a server, collect static files and if that passed do the database migrations.

But I had itchy feet. I’m not really a businessman at heart, so we closed the company and went our separate ways. Around that time, startup fever was taking off in the North East of England. 

## Startup SoPost

I met a young hustler looking for someone who knew Django inside out to “build the address layer” for the internet. Before long, we were working together and pivoted into a digital product sampling platform called [SoPost][4]. Until then, I’d been good at getting things done — but not necessarily at scale. Over the next three years, I had the most intense learning experience of my life. We’d built the platform in Django, which was great — but when 3,000 people hit your server at once, you need to be ready for it. Stock Django will let you fail and very publicly. PGBouncer, caching and the ability to rapidly spin up instances to handle traffic based on loadbalancer information is critical. CI & CD was maturing into a modern workflow based on [Jenkins][5] and the [Git Workflow][6].

## Scaleup SoPost

By 2016, SoPost was growing fast. I was lucky to hire skilled people, and while I listened and learned, I felt pulled from engineering toward leadership. I didn’t mind it, but leadership is hard — balancing autonomy with clarity isn’t simple. Writing production code became difficult as other responsibilities pulled me away. By the end of 2016, I shifted fully into the CTO role. Being a CTO at a sub-100-person company is different from leading at scale, but it’s still an exec role: strategy, communication, and ensuring teams have what they need. I didn’t take the role because I was a great CTO — I took it because someone had to. As we scaled, vendor security reviews and GDPR came into focus. I still wrote code, but only for the odd, persistent tasks: file transfers, DSARs, privacy 19assessments, controlled docs. I never stopped coding — just couldn’t stay in the sprint cycle. The bonus was that I became the person that those "weird customer specific" integration tasks came to. They keep my programming chops sharp and on my feet. 

## Being CTO

2016–2018 was another intense learning phase. InfoSec, data protection, cybersecurity, IT fleet management, contracts, and a lot of HR landed on my desk — the reality of scale-ups with no room yet for full-time roles in those areas. The code I wrote was mostly glue code, often in Python. The company had moved to Elixir and Elm for production, but glue work wasn’t easily done in Elixir — it was still a niche language in 2018. 

I was also getting tired of having to explain to customers why we were not on a track to getting ISO27001 when in procurement pipelines. The big globals expect you to have an ISMS and if you do, then it's the difference between &hellip; actually let me explain it in elixir.

```elixir

case infosec_posture do 
  # you have ISO27001 - great, 2 Questions, 1 certificate
  {:isocertified, true} ->
    [q1, q2]
    |> answer_question
    |> collect_evidence

  # you do not have ISO27001 - oh dear 😱
  # firewall rules, list of downstream supply chain
  # data protection impact assessments, access control
  # secure software development policy ... etc etc
  {:isocertified, false} ->
    1 .. 261 
    |> answer_question
    |> collect_evidence
end
    
```

So I went and got certified as an [ISO27001 lead implementor][7] and by early 2019 we'd got board sponsorship to set up the Information Security Management System (ISMS). The plan was to have it be compliant and complete first and second stage audits by summer 2020.

## Woodlands as Systems

When the global lockdowns hit, everything changed. I live in a dense urban area, but by good fortune I overlook a young, early-mature woodland growing atop an old colliery slag heap. Before lockdown, I hadn’t really seen the trees. But from March to July, I watched them spring into life as I worked at my desk. I didn’t know much about woodlands then, but I clearly remember the ground and field layers emerging first, followed by the shrub layer, then the understory, and finally the canopy. It was a system — not like the pipe systems I drew as a child, but a system of nature. I sat in my office chair (well, bedroom technically), watching a planet-wide system that could deploy anywhere and sustain itself. In this system, bugs were a feature.

## SoLong

By the end of 2021, things had mostly calmed down, and as a business, we finally came together for the first time since 2019. As CTO, I was used to public speaking and quite enjoyed it. I got up to give a talk to 120 people called something like “Why Your Day and IT Should Be Boring.” I walked on stage and took a photo of everyone. Then something happened. Just like hearing myself on Radio 1 at a party years ago, I felt joy and uncertainty. The joy was that whatever I’d set out to do at SoPost had been done. The uncertainty was: What now?

Back in 2003, that question was easy to mask with another drink. But a) I’ve been teetotal since 2007, and b) I had 120 people in front of me expecting an engaging talk. I delivered it, but it was a slog. The next day, I informally resigned, and we agreed on a nine-month notice period. I'd been at the company since its inception nine years earlier. I didn't want any bumps in my exit and we still had to complete the ISO27001 audits. Personally, I had no idea what was next for me. It was a total leap of faith (_or a midlife crisis - it is hard to tell them apart_) — but I had until October 8th, 2022, to figure it out. I was tired. I’d been working flat out since 2004 without pause.

## Trees & Code

In March 2022, for various reasons, we bought an eight-acre parcel of a 222-acre ancient semi-natural woodland. I remember thinking: I could either learn to work with trees — climbing, pruning, managing windfall — or pay a fortune for others to do it. So I enrolled in a two-year Forestry & Arboriculture course at Houghall Campus in Durham and it started that September. 

The plan was to earn an income through my third limited company, Trees & Code, doing software contracting around my studies. Once the [tree work qualifications (“tickets”) started coming in from 2023–24][8], I was spending more time up trees than writing code. In hindsight, I needed the break — from desks, chairs, and being indoors every day. My GitHub activity in 2023 and 2024 reflects that. When I wasn’t doing my own tree jobs, I was doing other tree jobs. When I wasn’t on a tree job, I was in my woodland. Or someone else’s. I was still writing code, but not a lot. I wasn't sad about this as I was earning on tree work.

But paradise had its cracks.

## Physical Reality

I’m approaching fifty. I carry it well, but the abundance of magical self-healing hormone are long gone. Tree work is tough — tree workers are [industrial athletes][9]. If you’ve done physical work all your life, you can keep going into your seventies with athlete-like habits: good sleep, good food, discipline. But starting in your late forties? That’s a stretch. After two years of hammering my body daily, I wasn’t just sore — it was the kind of pain that hints at knee replacements and rotator cuff issues.

Back in 2010, I completed a PGCE in post-compulsory education. I never used it — until a teaching role opened at the college I’d just graduated from. I’d passed the "Advanced Technical Diploma in Forestry and Arboriculture" with a triple star distinction 😇 and as a result they offered me the role of Lecturer in Trees & Woodland Management. I accepted and started in August 2024. There was a catch: my colleagues taught practical, I taught theory — and theory takes prep. I knew that going in, but I think my ego underestimated the effort. My body, meanwhile, needed the rest.

## Teaching

Starting at the college felt familiar — digital calendars were back, and weather didn’t affect your clothing. But it also felt alien: everything was Microsoft Office and Windows 🤢. My plan was to teach during the week (on a salary half that of tech) and do tree work on weekends to build up business funds for a van, quad bike, trailer — maybe even a micro digger. I already had saws, climbing gear, and rigging kit. I'd eventually make up the difference in salaries from dividends from the business.  The reality was that evenings and weekends vanished into lesson planning.Progress felt painfully slow and very dumb. In Big O terms, it was `O(n!)`. Teaching nine lessons a week, every week, with no room to slip on planning — it’s a special kind of hell. 

I was spending all my time in a room, at a desk, so that I could do my job in another room, at another desk, to talk about trees and look at them on a screen or through a window. There was no time for tree work — however, I massively leveled up in tree science, woodland management, ecology based legislation, and teaching. But I was starting to think I'd made a career mistake.

## Christmas 2024

By Christmas 2024, I was beyond exhausted. I'd only been teaching for three months. I could’ve worked in the woodland, but all I wanted was sleep and stillness. I’d never known tiredness like it — not just physical, but the relentless mental fatigue of always needing to be ready for the next day is punishing. Weirdly you don't notice it until its not there anymore and you wonder how on earth you managed it. 

My Christmas plan: sit down, watch YouTube (_of people doing tree work_) and rest. But then I opened a terminal on my machine. “What version of Django is current?” I thought. 

```python
mkdir -p ~/Desktop/foo && cd $_
python3 -m venv .python
source .python/bin/activate
pip install --upgrade pip # Sigh
pip install Django
django-admin startproject foo
cd foo
python manage.py runserver
# and open http://127.0.0.1:8000
```

Hmm, “What’s changed?”  “Let’s have a play…” Two days later, I’d built the seed of an app that I called "[Dendromeda][10]". YouTube was off, and I was back in the flow — falling asleep thinking about code, waking up excited to write it. I was dreading return to work as it meant once again entering into a cycle of perpetual `O(n!)` powered stress and exertion. I didn't for one second expect to rekindle a joy writing code. I had told myself a story that I'd left tech for a brave new career. My mind started thinking about possibilities and I'd started to narrow in on some concrete choices.


## 2025 New Year Resolutions

I'd decided that my spare time was going to [Dendromeda][10] — a tool to survey and manage tree populations. It was perfect for me as it combined Trees & Code (_my company is called Trees & Code_). But I quickly realised two things: my typing was terrible because I'd never taken the time to learn to touch type, and I was rusty as a programmer. Also, I’d only ever focused on one language at a time in my career and I was ready to embrace the journey of becoming a language agnostic software enginner - albeit a self-taught one. I'd always admired those people that I worked with who could seemlessly pick up a language. I'd decided to choose to be that person.

So, with New Year approaching, I made five resolutions:

1. No more planning college work during personal time.
2. Learn to touch type properly, like the engineers I admired at SoPost.
3. Design myself a basic computer science curriculum and become language agnostic.
4. I would seek out a position as a programmer. It has to be remote and ideally four days a week. I'd take five on my first job, but after that four was mandatory. Time is precious.

I planned to resign from the college on 11th July 2025.

## Resigned

I actually resigned on January the 8th 2025. My last day was March 14th, which was enough time to get the students through their exams. Again, I didn't really have a plan, just a commitment. Since I resigned, I've written more code three months than I have in the previous three years. In short, I'm back but this time, I've got a balance.

## The Stories we tell ourselves

I meditate. One of the ideas in meditation that you're working on is that you are who you decide to be. You’re not really you. You’re the residue of your choices and the result of the stories you tell yourself. I've told myself a bunch of stories over the years. I’m a drummer and so I ended up in a Band. I’m a web designer and developer and so I ended up running a web design and development company. I’m a lead engineer in a startup company, I’m a CTO in a scale up, I’m a CIO in a scale up. I'm the guy who's left tech to go work on trees. At start of each of those chapters there was a story that had a beginning a middle and an end.

Meditation teaches that three states define conscious life. There's the bit where you notice you're distracted. Then there's the bit where you are distracted. Then finally there's the bit where you recover from the distraction and become aware.

I've told myself a number of stories. They have a start a middle and an end. Everything does. The story I'm telling myself now is that my name is Jamie Curle. I live in Northumberland, UK. I write code, I’m an arborist and I manage my own ancient semi-natural woodland.






[0]: https://www.oreilly.com/library/view/perl-cookbook-2nd/0596003137/
[1]: https://en.wikipedia.org/wiki/ActionScript
[2]: https://docs.djangoproject.com/en/5.2/releases/0.95/
[3]: https://cvs.nongnu.org/
[4]: https://sopost.com
[5]: https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow
[6]: https://www.jenkins.io/
[7]: https://app.skillsclub.com/credential/17832-914727d802d1118e519f04329aed2c99c0a7bd3b6686dbaff54daec8f7136b73
[8]: https://www.credly.com/users/jamie-curle
[9]: https://pubmed.ncbi.nlm.nih.gov/12441489/
[10]: https://seed.dendromeda.com/