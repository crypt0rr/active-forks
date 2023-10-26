# active-forks

> Find the active github forks of a project

_NOTE: Looking for maintainer(s) to keep this project going_

While I want to be able to spend some time on this, I've had a lot of changes in life in general
and thus can not spend as much time on this repo. If you are interested in taking over to maintain
this project, please file an issue.

This project allows you to find the most active forks of a repository.

[Find Active Fork](https://saf.offsec.nl)

## As Bookmarklet

If you would like to use this tool as a bookmarklet,
you can do so by saving the following javascript code as the bookmarklet.
Since Github doesn't allow javascript in its markdown, you can add it manually.
Hit `Ctrl+D` to create a new bookmark and paste the javascript below into the URL
or "Location" entry (you may have to click "More" to see the URL field).
Any time you're on a Github repo you can click the bookmarklet
and it'll bring up the Active Forks of that repo.

```javascript
javascript:!function(){if(title=document.title,title)if(thing=title.split(/(GitHub\s-\s)*([^:]*)/)[2],thing){var t="https://saf.offsec.nl#"+thing;window.open(t)}else window.alert("Not%20a%20valid%20GitHub%20page")}();
```

![Screenshot](screenshot.png "Active Forks in Action")
