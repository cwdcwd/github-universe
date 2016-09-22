# Github Universe!

# What was it?
Github Universe is an awesome event, hosted by Github, to showcase and celebrate Github, the Github ecosystem, and software development (both open and closed) in general. 
![universe](https://raw.githubusercontent.com/cwdcwd/github-universe/master/images/2016-09-14_170909840_FEE30_iOS.jpg)

## Some amazing developments
- Platform enhancements:
  + Code Reviews on PRs
  + Projects Kanban
- Breakout sessions
  + Electron apps & `electron-compile`
  + GraphQL
  + Some git tips & tricks
- Some other interesting things
  + Code.gov
  + [Operation Code](https://operationcode.org/)
  + Investing in Future of Developers

### Platform enhancements
- Code reviews on Pull Requests are an awesome new feature of the Github platform. You can now gate acceptance of PRs based on code reviews and have an interactive conversation with submitters. Another tool in the tool box for quality and flow control on your projects. Awesome stuff.
- Projects Kanban now available inside Github repos. Hot on the heals of [Gitlab's](www.gitlab.com) [issue board announcement](https://about.gitlab.com/2016/08/22/announcing-the-gitlab-issue-board/) is [Github Project Boards](https://help.github.com/articles/tracking-the-progress-of-your-work-with-projects/), a very nice [project kanban](https://en.wikipedia.org/wiki/Kanban_board) for tracking progress. 

### The Breakout sessions

#### Electron apps!
Electon is the awesome node.js-based framework for building out cross-platform desktop apps. Wicked fast and super powerful, you can use a variety of standard JS/CSS techniques inside your Electron apps. But what if you wanted to do more than the usual stuff? [Machisté Quintana](https://twitter.com/mnquintana) of Slack gave a great presentation about `electron-compile` entitled _Making Electron Development Simpler, More Pleasant, and More Productive_. `electron-compile` is an awesome tool they developed to enable usage of higher level languages & tools and more complex systems inside your Electron app's build process. The project can be found [here](https://github.com/electron/electron-compile). [This post](https://slack.engineering/using-es2015-with-electron-introducing-electron-compile-2a0e5ccbadb6#.m6c51eqo9) actuall sums it up quite well. Net-net, `electron-compile` seems like a must have for the more involved Electron projects. Here at Topcoder we've actually been tossing around the idea of developing an Electron-base, TC-specific IDE. Reach out to me if you're interested. 

#### GraphQL
This is by far my favourite topic from the event. GraphQL is a brand new way of thinking around data querying and manipulation. The core concept being that we should have less rigid RESTful interfaces and datamodels and instead focus more on thinking about the "graph" of information as it aligns to the products we're building. 
//TODO insert https://graphqlbaer-test.herokuapp.com/graphQL with more fleshed out schema
![graphQL](https://raw.githubusercontent.com/cwdcwd/github-universe/master/images/2016-09-14_180044366_9F29B_iOS.jpg)

#### Tips & Tricks!
To me, one of the greatest things about git is that there's always something to learn. A new techinque, a flow pattern, or even just a simple CLI flag that I had _no_ idea about but changes the game for me on a day to day basis. Here's a couple I thought I should share:

- git CLI 
  + `git grep`: grep search your repo!
  + `git log --graph --full-history --all --color --pretty=format:"%x1b[31m%h%x09%x1b[32m%d%x1b[0m%x20%s"`: amazing pretty print log graph
  + `git status -sb`: short form status
  + `git add -p`: add partials to the stage instead of whole files
  + `git rebase -i`: interactive rebase  + 
- github.com
  + forked repos can receive branch updates from source
  + anchors on line numbers can actually span ranges; i.e: 12-24
  + can use commit message closes on titles as well as the issue #numbers
  + can filter PRs by status in issues list view
  + gists themselves are full repos
- Atom IDE
  + `alt-g`: change marker showing a marker on lines changed
  + `cmd-shift-p`: command palette
  + Some handy packages
    * markdown preview: uhhh previews markdown, of course
    * merge conflict resolution: highlights merge conflicts
    * git-time-machine: view history in a neat visualization
    * markdown-pdf: converts MD to PDF

### Some other interesting things

#### Code.gov
The US Goverment has announced ... stuff //TODO insert blurb here
![code.gov](https://github.com/cwdcwd/github-universe/raw/master/images/2016-09-14_174551225_152BA_iOS.jpg)

#### Operation Code
[Operation Code](https://operationcode.org/) is a great non-profit designed to help military veterans get trained in software development. OC provides the infrastructure for match-making technical volunteers with Vets for education and training in the software space. Great stuff.

#### Investing in Future of Developers
Much of the keynotes spoke about the future the software, and tech industry in general, and how we're likley facing a labour gap in the space. //TODO insert slide shot here
![future](https://github.com/cwdcwd/github-universe/raw/master/images/2016-09-15_170819382_3A36D_iOS.jpg)


### Conclusion

![octokat](https://raw.githubusercontent.com/cwdcwd/github-universe/master/images/2016-09-15_180253690_E637B_iOS.jpg)
