if you have been working in software engineering in recent years, especially in server or backend systems, you have probably been bombarded by plenty of buzzwords like nosql, cap etc.
in the last decade, we have seen many intersting developments in databases, distibuted systems and in the way we build applications on top of them, there're various driving forces for these developments
- big internet companies are handling huge volume of data and traffic, which force them to create new tools that enable them handling such scale efficiently
- bussinesses need to be agile, test hypothisises cheaply and respond to new market insights rapidly by making the development circle short and data model flexible
- free and open source software have been very successful, and now is prefered to commercial and in-house softwares in many enviroments
- CPU clock speed are barely increasing, but multi-core processor are stardard and network are getting faster, which means parallisism is only going to increase
- even you are working on small teams, you can now create applications that are distributed on many machines and across multiple geography regions thanks to iaas eg. aws
- many services are expected to be highly avaliable, down time due to outage or maitainence are increasingly unacceptable

data intensive applications are pushing the boundary of what's possible by making use of these developments, we call an application data intensive if data is its primary challenge - the volume, the complexity and the speed at which it is chaning. as opposite to compute intensive application, where CPU circles are their primary bottleneck

the tools and technolegies that help data intensive applications to store and process data are rapidly adapting to these changes, new database systems have been getting a lot of attentions, but message queue, caches etc are important as well, some applications use a combination of some of them.

the buzzwords that fill this space are a sign of ethusiasm for new possiblities, which is great, but as software engineers and architechs, we also need to have a technically accurate and precise understanding of the various technoleges and their trade-offs if we want to build good applciations, for that understanding we have to dig deeper than buzzwords.

fortunately behind the rapid change in techonodeges, the princiles remain true no matter which version of particule tools you use. if you understand those principles, you are in a position that sees where each tool fit in, how to make good use of them and how to avoid the pitfalls.

the goal of this book is to help you navigate through the diverse and fast changing landscape of of technoledges for processing and storing data. this book is not a tuturial of particular tool, nor is it a textbook full of dry theories. instead, we'll look at examples of successfully data systems - the technoledges that form the foundation of popular applications and that meet the requirements of reliablility, scaliablity and maintainlibility in production

we'll dig into those systems, tease apart the key algorithms, discuss the principles and tradeoffs they have to make. on this journey we'll try to find useful ways of thinking about data systems - not only how it works but also why it works this way and what's are the questions we need to ask.

after reading this book you'll be in a great position to decide which technoledge is appropriate to which purpose, and understands how tools can be combined together to form the foundation of a good application architechture. you wont be ready to build your own data storage engine from scratch, but fortunately that's rarely neccessary. you will however develop an intuitition for what your system is doing under the hood, so that you can reason about their behaviors, make good design decisions and track down problems that may arise.

when talking about scalable data systems, comments are made along the lines of you are not google or amazon, so just use one rational database. there's truth in that statement, building for the scale that you don't need is wasted work and may lock you into an inflesible design.in effect it's a form of premature optimization, but also it's important to choose the right tool for the job, different technoledges each has its own strength and weeknees, as we shall see, rational databases are important but they are not the final words on dealing with data.
