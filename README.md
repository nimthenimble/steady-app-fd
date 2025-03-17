# Steady App Fix Documentation
Made with the [Hugo Framework](https://gohugo.io) the Stead App Fix Documentation is an archive for all the changes or adds I've made/suggested to make in the website, assets or any other content related to Steady. In order to run the website you will need to follow `# Installation` and you will require to have Hugo installed.
<br>
<br>
<br>

# Installation

1. **Step One - Install Hugo:**
In order to locally run **Steady App Fix Documentation** you will need to install Hugo (MacOS, Windows or Linux)

```
brew install hugo
```

You can read how install Hugo on [windows](https://gohugo.io/installation/windows/) or [Linux](https://gohugo.io/installation/linux/) in either of these links.

2. **Step Two - Create New Hugo Site**
```
hugo new site site-name
cd site-name
```

3. **Step Three - Clone This Repo**
```
git clone https://github.com/nimthenimble/steady-app-fd
```

4. **Step Four - Run Hugo Locally**
```
hugo server
```

And you'll have a preview of the site and all of the issues on the documentation.
<br>
<br>
<br>

# Keeping Your Fork Updated with the Original Repository

If you've cloned a repository and want to keep it updated with the changes from the original author, follow these steps:

1. **Step One - Check current remotes**
First, check the current remotes in your local repository to see if you have the original repository set as a remote.

```
git remote -v
```

2. **Step Two - Add the original repository as an upstream remote**

```
git remote add upstream https://github.com/nimthenimble/steady-app-fd.git
```

3. **Step Three - Fetch updates from the original repository**
```
git fetch upstream
```

4. **Step Four -  Merge changes into your branch**
```
git checkout main  # Make sure you're on the main branch
git
```
