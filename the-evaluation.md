## How does this evaluation work?

During the Odyssey Hackathon Software Improvement Group (SIG) Code JEDI will support the teams to write future-proof code by means of tooling and advice.

Teams will be invited to a GitHub team repo where they can push their code continuously. The repo can be a private or public (or remote git) repo. For every push BetterCodeHub (BCH) will automatically check the code quality. Installation of BCH is zero-setup. The code quality score is displayed on a 10 point scale. All the scores will be on a dashboard. All teams will receive a sticker with the final maintainability score for their canvas on Sunday. 

The teams that score a 10/10 qualify for a short interview by a SIG Code JEDI. During this 10 minute session the JEDI will ‘grill’ your tech lead on the software engineering choices made: choice of technology, code architecture, security concerns and blockchain implementation. On passing the ‘grill’ session a Golden Balloon is awarded, this will help you demonstrate the maturity of your prototype to the judges.

## Ok, what are those 10 guidelines?

1. Your code will be evaluated against 10 guidelines for building future-proof code. The guidelines are described in full in [“Building Maintainable Software”](http://shop.oreilly.com/product/0636920049159.do) (Ask for a free copy at the masterclass on [April 11th](https://Odysseyhack.github.io/masterclass))

2. Find a concise reference card of the guidelines [here](https://cdn-images-1.medium.com/max/1200/1*TS-ZTeI7sQS7dy_AlMqSXQ.png).

3. You can check your code against the guidelines using Better Code Hub, a GitHub integration provided by [Software Improvement Group](https://www.sig.eu). Better Code Hub integrates with the GitHub CI and can run at Pull Requests and Pushes.

4. 17 modern programming languages are [supported](https://bettercodehub.com/docs/configuration-manual) with a maximum codebase size 200 KLoc.


## GitHub teams and private repos

- All the teams were created on forehand and email invites were send to the teamleads. 
- Please check these invite emails from GitHub.
- Your team is added here [Odysseyhack Organization](https://github.com/odysseyhack)
- We have create a private repo for you.
- Your repo can be a 'Git Remote'

## More private repos

- You can add more repos to your team yourself.
- You first need to create the repository within the org (using the + next to your profile icon) 
- then add the repo to your team -> repositories -> add -> and add the created respository
- be aware of the weakest-link -principle

## GitHub oAuth to login to Better Code Hub and run analysis

1. Go to [Bettercodehub.com](https://bettercodehub.com), login with your Github oAuth and accept the 3 scopes. 

2. Press play and get instant feedback on the guidelines and pick refactor candidates.

3. Click on the Pull request icon to make Better Code Hub analyse every Push and Pull Request.


## How to get support

1. Before the event, through [email](mailto:bettercodehub@sig.eu).

2. During the event by talking to Better Code Hub JEDI with questions about refactoring tactics and code implementation. use 

3. At the Hackathon please use Odyssey community bettercodehub_support 

4. After the event, through [email](mailto:bettercodehub@sig.eu).


## How to get a sticker with my score 

1. The more guidelines you get right, the higher the final score.

2. if you have multiple repos the lowest scoring repo is your final mark (weakest link principle).

3. On Sunday April 14th between 9:00 and 11:59 ask for a sticker with your final score.

4. Put the sticker on the canvas.


## How to get Grilled

1. If you score a 10/10 then you qualify!

2. pick your 10 minute slot for your session

3. get Grilled..

4. if you pass you get a Golden Balloon



## Odyssey Hackathon Scoreboard

All the badges of the repos are collected [here](https://odysseyhack.github.io/scoreboard)
Not on the scoreboard? Let the Better Code Hub team know on Mobilize or send a PR.


## How to exclude library files from analysis / change your configuration

1. Get your current configuration file from your project settings. (Gear icon on bettercodehub.com)

2. PLace that config in _.bettercodehub.yml_ in your repository root

3. Add a section called exclude, in there add the files/folders you want to exclude. Supported exclusion options can be found [at the bettercodehub documentation](https://bettercodehub.com/docs/configuration-manual)


## Why your Odyssey needs Future-Proof code

Read more [On why it needs high quality code ](https://medium.com/@jstvssr/why-blockchain-needs-future-proof-code-cb09b39175e1#.bqfmcig55)

Or about the [2017 Dutch Blockchain Hackathon in Groningen](https://dev.to/jstvssr/how-a-hackathon-appreciates-quality-code)


Let's build some great software!!

[Jade](https://github.com/jadeheiligers), Hugo, Bugra, [Jan](https://github.com/janlaan), [Michiel](https://github.com/michielcuijpers)

