# Topics
1. News
2. Abandonned stuff
3. Dev Feature Requests
4. Biotope Element next steps

## 1. News

### Resource Loader v2
- Handlers
- Different bundles

### Style-Guide
- We would like to rename it to __biotope-component-preview__
- Reconsider Storybook (has now html support)
- http://airbnb.io/react-dates/?selectedKind=SDP%20-%20Input%20Props&selectedStory=with%20show%20calendar%20icon%20after%20input&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybook%2Factions%2Factions-panel
- Take care that it is not customer specific
- Futureproof
- No rebuilding of existing tools

### Boilerplate
- No more jquery
- Typescript Boilerplate

### CLI
- biotope init

## 2. Abandonned stuff
### Abandoned Repositories
We should be able to delete unused repositories when we get no answer. I.e.:
- World Domination Grid
- Json Server

__Proposal__:
We create a dependency tree for all the projects, to get a clear picture what their responsibility is.

### Stale branches
If the last commit is older then six months, the branch should be deleted, even its not merged.
Except for master/version branches. For version branches we will transform them to tags and put them onto npm.

### Stale issues
After six months the tickets should be closed. If this is not the case and there is no activity they will be automatically closed.


## 3. Feature Requests
We want to get more insights onto what the biotope developers want. We want to tackle real issues for the real use cases.
How can we encourage our coworkers to contribute?

Our mantra: **Don't say no! Enable instead of do it for them.**


## 4. Biotope Element
We want to have a good developer experience. For that we need to improve some things. 
Next steps:
- Create organization board with tickets that need to be done
- Add examples to biotope-element documentation (SeeTheExampe instead of ReadTheManual)
