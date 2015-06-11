Wikitree
===============
Alex Burner
aburner@uw.edu


Wikitree was built for both the Informatics capstone project and the CSE 512 final project concurrently. For CSE 512 I was the only team member, but for the Informatics capstone I was on a team with James K Prow and Christina K Xiao. James handled Digtal Ocean setup, Angular architecture, routing, and sessions logic. Christina was our project manager. We all participated in strategy, feature brainstorming, research interviews, and user testing.

I came up with the idea for Wikitree in September of 2011, but it's taken me this long to find the time, talent, and team to be able to pull it off. I hope you enjoy!


[![summary](summary.png)](https://wikitree.website/)


Wikitree is a web application built to help undergraduates with their research. Wikitree tracks and organizes the user's browsing history through Wikipedia articles. Wikitree is unique because it emphasizes mental connections the user makes. Wikitree aims to stay adaptable for each individual's research goals. Our research and user testing revealed many struggles undergraduates have. They struggle to dive deep into one topic while staying aware of the big picture. They struggle to mentally categorize connections between different topics during early stages of research. They struggle with feeling overwhelmed by the amount of material encountered, and finding a clear vision within. Wikitree acts as an aid for the user in tracking their explorations. The visualization helps users maintain a high level overview, preventing them from feeling overwhelmed, getting sidetracked, or losing sight of their goals.

Special thanks to Michael Freeman, Jeffrey Heer, Jessica Hullman, David McDonald, Nam-ho Park, Jason Porteno, David Stearns, and Jevin West.


[Poster](https://github.com/CSE512-15S/fp-aburner/raw/master/final/poster-aburner.pdf),
[Paper](https://github.com/CSE512-15S/fp-aburner/raw/master/final/paper-aburner.pdf),
[Page](http://cse512-15s.github.io/fp-aburner/)


## Running Instructions

Prereq: ensure you have `node`, `gulp`, and `bower` installed

Fork & clone both the main repo and the env repo (these are designed to live as sibling directories)
- Main repo: https://github.com/wikitree-website/wikitree
- Env repo: https://github.com/wikitree-website/wikitree-env

For 512, there are duplicates of these repos in this repo
- Main ~~repo~~: https://github.com/CSE512-15S/fp-aburner/tree/master/code/wikitree
- Env ~~repo~~: https://github.com/CSE512-15S/fp-aburner/tree/master/code/wikitree-env

In the main repo, run:
```
$ npm install
```
(which should also trigger `bower install`)

Then, for production, run:
```
$ gulp build
$ npm start
```

Or, for development, just run:
```
$ gulp dev
```

Congrats! In development, the app should be available on:
- [http://localhost:1111](http://localhost:1111)
- [https://localhost:2222](https://localhost:2222)
