# Reusable components

Every agnostic component (UI control, category, helper, etc) should be created in a separate repository and in Swift.

Your component should be unit tested and documented.

# Steps to create a component

- [ ] Create repo on GitHub
- [ ] Go to your Projects folder
- [ ] Run `git clone https://github.com/bakkenbaeck/swift-library-template <PODNAME>`
- [ ] Run `cd <PODNAME>`
- [ ] Run `./init.rb <PODNAME>`
- [ ] [Enable Travis for your repository](https://travis-ci.org/profile/eradotmedia). If your component doesn't show up press "Sync Now"
- [ ] To test your pod in another project while developing it you have to make sure all changes of your pod are commited and synced, then make sure `pod '<YOUR_PODS_NAME>', :git => 'https://github.com/eradotmedia/<YOUR_PODS_NAME>.git` is in the other project's Podfile. Running `pod install <YOUR_PODS_NAME>` (first time) or `pod update <YOUR_PODS_NAME>` (after each change to your pod) in the other project is required
- [ ] Add your beautiful code and make a `Initial implementation` pull request
- [ ] Publish your pod by running `pod trunk push`(*)
- [ ] Add era as co-owner by running `pod trunk add-owner <PODNAME> developer@era.media`
- [ ] :cake:

(*) If you don't have a CocoaPods account you can create one by following [this steps](http://guides.cocoapods.org/making/getting-setup-with-trunk.html#getting-started).

# Steps to ship your component

Before shipping your component make sure that the README states what makes your Pod different than the other ones, been made by you might not be enough. It's very important that your README is :star2: fabulous :star2:.

Make sure to provide a super simple example on how to get your Pod up and running, if it is dependent on other Pods you should explain why you need them and what they do. Don't assume that people know everything.

If it's a visual component include a `.gif` showing how does it work or what does it do. It helps a lot for people to understand your Pod without having to clone, build and run your project. A good tool to make gifs is [Licecap](http://www.cockos.com/licecap/) or [ezgif](https://ezgif.com/).

- [ ] Make sure to have a cool logo
- [ ] Submit it to [Cocoa Controls](https://www.cocoacontrols.com/)
- [ ] Make a PR to [iOS Goodies](https://github.com/iOS-Goodies/iOS-Goodies)
- [ ] Submit your component to [Hacker News](https://news.ycombinator.com/), your post should start with **Show HN**

**Send a few tweets from the @eradotmedia account**

Always express yourself like you are part of a team, use **"We did this"** and never **"I did this"**.
Take the time to compose personal tweets to all your recipients, copy pasting one message to everyone makes you sound like a robot and feels spammy, don't do this.

- [ ] Send a tweet from the [@eradotmedia](https://twitter.com/eradotmedia) account with a tiny summary and attach the logo of the Pod
