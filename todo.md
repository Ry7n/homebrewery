# The Homebrewery

## v1.5 todo
X Make statusbar un-fixed
X Simplify the panel css to remove the current issues
- Build new `BrewRenderer`, clean support for partial rendering
- Add `infoBox` to BrewRenderer to show views, and current pages
- remove old status bar
- Add in markdown editor
- Add bleed snippet (bump)
- Add the '/new' page and force save to reduce database size
X Add pagniation and query to the homebrew api
X Update the admin page with pagnition and a query box
X Test the old/small brew filtering for deleteion
- Partial rendering kills style tags on unrendered pages. Detect if pages have style tags and render them.
- Add in the link of Pateron?

- Add in a tutorial page?

## v1.6
- Add error handling to the saving wdiget in the status bar
  - Should provide error dump to copy and a link to github issues page
- Add in the pane splitter
- Add in CodeMIrror of markdown
- Code Editor should display errors at bottom
- Add in Descriptive name box for a brew
- Look into improving the metadata on pages for linking


## v1.7
- User accounts!
  - Add a new database model
  - Make sure you salt those passwords
  - Add a new `/user/id` page
  - Should be able to change username and password
  - render and show all of thier brews
  -


# SpellSort

## v0.1
- Query text box
  - should support `has:somatic`, `class:wizard`, `school:divination`, `level:6`
- Add a dropdown box with clickable elements to inject search terms
- Clean up the 5th edition spells json

