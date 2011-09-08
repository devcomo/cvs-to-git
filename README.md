# From CVS to Git

### Another talk on Git?

Yes. Again. But this time, it's **For Science**. <small>(And some people who still use CVS.)</small>

In [my previous talk][4] I gave you knowledge on Git in general; how it
does it's magic and introduced you to some basic branching and merging.

On this trip we'll compare CVS/SVN and Git, and explore how to use git and play nice with others.  

**T**able **O**f **C**ontents

1. Intro
	- About git, history
2. Comparing to CVS
	- Common terms
	- Key differences (commit vs push, DVCS)
3. Git and Teams
	- Integration Manager strategy
	- Github
	- Commits, Branching and merging
	- Pull requests

# Viewing the slideshow
This is a [ShowOff][3] presentation about **Moving from CVS to Git**.

You can view the presentation here: [http://ctshryock.github.com/cvs-to-git][6]

If you want to view it locally, you need to install Showoff, clone the repo, and then run `serve`:

    $ gem install showoff
    $ git clone git://github.com/ctshryock/cvs-to-git.git
    $ cd cvs-to-git
    $ showoff serve

Go to [http://localhost:9090][5] to view the presentation.


[3]: http://github.com/schacon/showoff
[4]: https://github.com/ctshryock/GitTalk
[5]: http://localhost:9090
[6]: http://ctshryock.github.com/cvs-to-git