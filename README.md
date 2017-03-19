# Awesome Auto Nomie
> Curated list of tools and setups for automated data tracking w/ Nomie Pro

Contributions welcome. Add links, instructions, or code through pull requests or create an issue to start a discussion.

[Nomie](https://nomie.io) is a powerful tool for tracking and aggregating your personal data. The [Nomie Pro API](https://connect.nomie.io/#/) allows you to programmatically track anything.

## Contents
- [IFTTT Scripts](#ifttt-scripts)
- [DIY Programs](#diy-programs)
- [External Plugins](#external-plugins)
- [Cloud Apps](#cloud-apps)
- [Near Automatic](#near-automatic)

## IFTTT Scripts
[IFTTT](https://ifttt.com) is a powerful tool that enables you to connect "channels" and have events trigger actions.
- **Strava Runs** - Link up the [Strava Channel](https://ifttt.com/strava) and then create a new Applet with the trigger `New Activity By You`. Next, add the action as a Maker channel request similar to `https://api.nomie.io/v2/push/[myKey]/action=track/label=Run/value={{DistanceMeters}}`

## DIY Programs
- [**Todoist to Nomie**](https://github.com/huberf/TodoistToNomie) - Log the completion of Todoist tasks based upon their folder name and priority.

## External Plugins
Plugins and add-ons for applications other than Nomie (e.g. git, vim, Visual Studio Code)
- [Git Commit Logger](https://gist.github.com/thejeshgn/c81d784a8a81db41f97eaa6c5d4f6ffb) - You can add this to your Git setup via instructions found at [this gist](https://gist.github.com/thejeshgn/c81d784a8a81db41f97eaa6c5d4f6ffb).

## Cloud Apps
- **Weather Tracker** - This Cloud App logs the temperature and humidity daily. Add it through the `General` tab in the Cloud App store.

## Near Automatic
Tools and workflows for Nomie tracking that are so close to automatic they deserve to make the list.
- [Garmin Watch Nomie Tracker](https://gist.github.com/huberf/8ecf6d3514e11ada83e6164789b4e37b) - This [Gist](https://gist.github.com/huberf/8ecf6d3514e11ada83e6164789b4e37b) details to the steps to setting up an easy to use "button" to quickly track up to four trackers with a simple tap.
