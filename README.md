# Awesome Auto Nomie
> Curated list of tools and setups for automated data tracking w/ Nomie Pro

Contributions welcome. Add links, instructions, or code through pull requests or create an issue to start a discussion.

(Nomie)[https://nomie.io] is a powerful tool for tracking and aggregating your personal data. The (Nomie Pro API)[https://connect.nomie.io/#/] allows you to programmatically track anything.

## Contents
- [IFTTT Scripts](#ifttt-scripts)
- [DIY Programs](#diy-programs)
- [Cloud Apps](#cloud-apps)

## IFTTT Scripts
- **Strava Runs** - Link up the (Strava Channel)[https://ifttt.com/strava] and then create a new Applet with the trigger `New Activity By You`. Next, add the action as a Maker channel request similar to `https://api.nomie.io/v2/push/[myKey]/action=track/label=Run/value={{DistanceMeters}}`

## DIY Programs
- [**Todoist to Nomie**](https://github.com/huberf/TodoistToNomie) - Log the completion of Todoist tasks based upon their folder name and priority.

## Cloud Apps
- **Weather Tracker** - This Cloud App logs the temperature and humidity daily. Add it through the `General` tab in the Cloud App store.
