# Socialise - a simple site for the social

Socialise is a simple site for even the less web-savvy. Just find links to your profiles for each social network you want to go public, and the rest is done for you. If you've got an inkling about what to do with web development, Socialise is a minimal template for you to work off - great for first timers. And if you haven't...it's as simple as this.

## Installation

1. **Fork** this project to your GitHub account using the Fork button up top.

1. In the settings for your fork, **rename the project** to `yourusername.github.io`, where `yourusername` is your GitHub username. From then on, Socialise will be live at that web address, `yourusername.github.io`.

1. **In your fork of the project, change the profile in `data/_profiles.yml`**. Replace `JohnDoe` with what's at the end of your profile links. For example, if you view your personal Facebook profile, your browser will be at `facebook.com/your.username` or something like that. In this case, put `your.username` where JohnDoe is. If you don't have an account for a shown service, simply delete that line. **I'm aware some profiles can be hard to find (looking at you Spotify!). Instructions coming to the wiki soon.**

You can also **deploy with Heroku** - instructions available soon. 

I'll admit that right now this is a little heavy-handed, but relatively speaking, it's still far less of an investment of time (or money!) than most people would put into making a website.

## Updating

To update your version of the site to use the current version of socialise, run the following in a Git terminal environment:

```
git remote add upstream https://github.com/boardfish/socialise
git fetch upstream
git checkout master
git merge upstream/master
git push
```

## Additional Notes

- **2017/12/27** - CV option added. Note that I personally don't recommend using this alongside your more personal outlets like Steam, Facebook etc. Create a folder called `files` and put your CV in there - it can be in any file format. Set the `cv` variable to the full name of the file, such as `CV-JohnDoe-20171227.pdf`, and the link should work just fine.
