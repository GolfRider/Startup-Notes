# Startup / Important - Notes

These are some of the few bookmarks on various topics ranging from technology, startups, self-help to business.
It may not be properly organized. They say, don't chase perfection, just do it.
Sometimes knowledge doesn't help, so take everything with a grain of salt  :-)

## Startups / Enterpreneurship
1. How to start a company with no free time:
     https://medium.com/startup-grind/how-to-start-a-company-with-no-free-time-b70fbe7b918a/
2. Success Stories / Lessons Learned:
     https://urchin.biz/urchin-software-corp-89a1f5292999  (Read the summary)
   
3. The only enterpreneurship lesson you ever need:
     https://medium.com/startup-grind/the-only-entrepreneurship-lesson-reading-list-you-need-105d9e3bcf5a    
4. http://klinger.io/   
5. HN/Techcrunch/Reddit (as always)  
6. https://www.indiehackers.com/businesses 
7. http://www.slideshare.net/laurenthaug/things-i-will-tell-my-kids-if-they-become-entrepreneurs
8. http://www.slideshare.net/ActivateInc/activate-tech-and-media-outlook-2016
9. https://www.linkedin.com/pulse/its-all-start-abhishek-roy

## Product Design/Prototyping
1. https://techcrunch.com/2016/11/29/the-future-of-front-end-development-is-design/
       

## DataScience / ML
1. http://blog.mailgun.com/machine-learning-for-everyday-tasks/
2. https://hackernoon.com/wannabe-data-scientists-learn-the-basics-with-these-7-books-1a41cfbbdd34
3. https://machinelearningmastery.com
4. http://data36.com/ (good, easy to understand articles)
5. http://data36.com/predictive-analytics-101-part-1/ (from above blog)
6. http://pythonforengineers.com

## Chatbots / Messaging / App Fatigue (Text, AI) 
1. https://www.techinasia.com/talk/complete-beginners-guide-chatbots
2. https://chatbotsmagazine.com/the-complete-beginner-s-guide-to-chatbots-8280b7b906ca
3. https://medium.com/assist/http-gph-is-1uxlkf2-ba8be0681379 (good one)
4. https://medium.com/assist/money-from-messaging-the-impact-of-brands-in-the-messaging-ecosystem-192e99481919

## Alexa (Voice Interface)  + Touch Interface Combo
1. https://dzone.com/articles/implement-a-custom-alexa-skill-using-spring-cloud-1
2. https://techcrunch.com/2016/11/29/amazon-said-to-plan-alexa-speaker-with-7-inch-touchscreen-for-2017/

## Connected/ Smart Cars
1. https://techcrunch.com/2016/11/29/bmw-daimler-ford-and-vw-to-build-high-power-european-ev-charging-network/

## Blockchains 
1. http://blockgeeks.com/guides/what-is-blockchain-technology-a-step-by-step-guide-than-anyone-can-understand/
2. https://dzone.com/articles/blockchain-basics-and-opportunities-with-anna-derb

## Career/Interview Notes/ Programming
1. https://www.reaktor.com/blog/how-to-grow-into-your-best-developer-self/
2. https://www.reddit.com/r/cscareerquestions/comments/1jov24/heres_how_to_prepare_for_tech_interviews/
3. https://medium.freecodecamp.com/5-key-learnings-from-the-post-bootcamp-job-search-9a07468d2331
4. https://dzone.com/articles/how-to-turn-your-github-page-into-a-personalized-r
5. https://blog.remix.com/an-intro-to-integer-programming-for-engineers-simplified-bus-scheduling-bd3d64895e92
6. https://www.quora.com/Jobs-and-Careers-What-is-some-good-general-career-advice
7. http://www.crackingthecodinginterview.com/resources.html
8. https://www.quora.com/What-has-been-your-biggest-career-mistake [Good One from Quora]
9. http://katemats.com/interview-questions/ [Epic List of Questions]

## Effective Learning
1. http://www.simplydjango.com/learn-python-efficiently/   [Great Read..!]
2. http://jamesclear.com/successful-people-start-before-they-feel-ready
3. https://www.scotthyoung.com/blog/2015/04/01/finish-what-you-start/

## Software Engineer to Enterpreneurship ?
1. https://dzone.com/articles/dear-engineer-so-you-wanna-become-an-entrepreneur

## Self Help / Quotes / Productivity Tips
1. http://wiki.c2.com/?RubberDucking (Self loud talk approach to Problem Solving)
2. http://paulgraham.com/quo.html 
3. http://www.businessinsider.com/entrepreneur-making-135000-a-month-shares-productivity-hacks-2016-10
4. https://www.linkedin.com/pulse/its-all-start-abhishek-roy

## Focus / Productivity
1. https://www.linkedin.com/pulse/how-focus-things-matter-most-bruce-kasanoff

## Distributed Systems / Microservices
1. https://qconlondon.com/london-2014/dl/qcon-london-2014/slides/AdrianCockcroft_MigratingToMicroservices.pdf
2. https://qconnewyork.com/ny2015/system/files/presentation-slides/uberRUSH.pdf
3. http://projects.spring.io/spring-cloud/
4. https://zeit.co/blog/next# (NodeJS + ReactJS)
5. http://pivotaljourney.blogspot.com/2016/06/microservices-with-spring-boot-spring.html
6. https://spring.io/blog/2015/07/14/microservices-with-spring
7. http://callistaenterprise.se/blogg/teknik/2015/05/20/blog-series-building-microservices/ [Good and Concise]
8. http://callistaenterprise.se/assets/presentationer/microservices-sto.pdf
9. https://spring.io/blog/2015/07/14/microservices-with-spring
10. https://programmaticponderings.com/2016/02/15/diving-deeper-into-getting-started-with-spring-cloud/

## Distributed Systems Principles
1. Ciruitbreakers, BulkHeading, Rate Limiters, Loadbalancers
2. Fault/latency tolerant
3. Consistent Hashing:
        - Map servers + data to a logical ring
        - Map a request to a range
        - Request is handled by the server responsible for the range (cluster-size can vary dynamically ie, grow/shrink)
4. Message headers
5. Bloom filters (probablistic data structures) [not directly related, but still useful in many places]
6. Http/JSON is typically 20 times slower than gRPC/thrift ie, binary serialization/de-serialization protocols
7. CAP theorem
8. Hard Problems of distributed systems:
     -a. Exactly once delivery
     -b. Guaranteed order of messages
9. Microservices have operational overhead, so require good tooling/automation
10. Microservices are simple inside
11. Microservices are complex from outside/communications perspective
12. Look from these perspectives:
      - Organizational concerns
      - Architectural concerns
      - Developmental concerns
13. Unit testing is easy, integrated testing is hard      
      
## Effective Learning
1. https://news.ycombinator.com/item?id=13047576

## How To Ship Products
1. http://blog.andyjiang.com/how-to-ship-side-projects/  [Be a Finisher, finish what you start]
2. https://news.ycombinator.com/item?id=13119075
3. https://www.linkedin.com/pulse/how-focus-things-matter-most-bruce-kasanoff

## Tools / Web Design
1. https://www.smashingmagazine.com/2016/12/mistakes-developers-make-when-learning-design/ [Design Thinking]
2. http://launchaco.com/build/ (web site builder)
3. http://adventurega.me/bootstrap/
4. http://html5up.net

## Career Tips
1. https://news.ycombinator.com/item?id=13168798  [Advice to younger self]

## Lambda Calculus
1. http://www.cs.bham.ac.uk/~axj/pub/papers/lambda-calculus.pdf

## Security
1. https://www.crypto101.io/
2. https://www.owasp.org

## Programming Talks
1. http://www.opowell.com/post/talks-that-changed-the-way-i-think-about-programming/

## Microservices Design Principles
Data Flows :

- 1) Implement as pipelines (serial or parallel)
- 2) Pipeline consists of stateful and statelss services
- 3) Stateful services obtains data
- 4) Statelss services transforms data
- 5) See if you can model a given pipeline/transformation in a single service
     (ie, Pipeline/Orchestration Services, which are again stateless in nature)
- 6) Design systems in sync with reality
- 7) Data moves/flows through the system in a immutable way
- 8) Immutable data flows/pipelines
- 9) CQRS/ Event Sourcing evolution can be handled later in time
- 10) Separation Of concerns based on dataflows

- 11) Data Flow Concerns of the system
    - Lifecycle 
    - Size
    - Structure
    - Velocity
    - Purpose

- Separation of concerns should be applied to both (data + algorithms)
- Results in natural decoupling
- Ex: CQRS, Polyglot persistence, Microservices


- Decouple services (for indepenedent scalaing, evolution, operations)
- Decouple data models
- Define the domain in terms of service interaction, not service implementation
- Design services that have business meaning and clear boundaries
- Check Conway's law, Gattle's system law
  ie, Architecture follows the communication structure of the organization
- The essence of microservices is Collaboration
- Simplify the data model

Design Principles:
- 1. Simplicity
- 2. Decoupling
- 3. Distributed System
- 4. Conways Law
- 5. Gall's system law

References:
- 1. Nginx Ref Architecure:
     https://www.nginx.com/blog/introducing-the-nginx-microservices-reference-architecture/
- 2. http://nordicapis.com/
- 3. http://microservices.io/
- 4. auth0.com
   
 ## How to be successful
 - 1. https://www.linkedin.com/pulse/7-brutally-honest-reasons-why-youll-never-successful-how-zahir-serrai
 - 2. http://executivevine.com/executive/articles/7-painfully-honest-reasons-youll-never-successful/  [both have same content :-)]
 - 3. Important Points:
       - Have a clear vision of you want to accomplish, have your definition of success, as everyone is different
       - Don't be afraid to ask help when required
       - Being selfish doesn't help, it is important to help others to succeed 
       - Being generous is good for your health too
       - Have Disciplined Time management/ schedule:
           - Everyone is busy, but yet nothing gets done, why ?; Spend time in a mindful way
           - Time is more valuable than money
           - Schedule and prioritize your tasks
           - If you add something to your TODO lists, then remove something else
           - Find the 1 or 2 important things and do them first.
           - Do the most dreadful thing FIRST, instead of procrastinating it.
           - Always decide what we have to do with the time given to us.
       - Keep learning/improving yourself.
       - There are no shortcuts to success.
       - People generally are not ready to commit themselves for success.
       - They choose unhapiness over uncertainity, they don't want to leave their comfort zone.
       - Don't let failures paralyse your actions/thoughts at every step of the way
       - So, COMMITMENT is the SECRET ingredient.
       - Being successful is not about money, status or even reaching your goals, they are just the side effects
       - Successful peopl love what they do, no matter how simple/hard it is, they are deeply passionate about their GOALS.
       - So it is falling in love with the PROCESS every step of the WAY.
       - So it is loving what you do, loving your failures/triumphs, loving all those who help you along the way
       - More importantly, it is about LOVING YOURSELF...!!
       
