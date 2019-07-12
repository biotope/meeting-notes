# Topics

## Styleguide
We first changed the name of the tool to be named biotope-preview, as it is more than a traditional styleguide.
We clarified, what the preview should be, what it is right now, and what features there should be in it:

- the tool itself should be running from static files
- the developer should be able to compose components to demo pages
- it will contain styleguide information (colors, fonts, etc), all generated
- we definitely need the possibility to have some kind of container queries
- component variation showcases should be generated automatically
- we want to have a code view
- we want to show the components package name and registry
- we want it to be versioned

We defined the target groups for this tool:
- Project Owner/Project Manager
- Designer/Concept
- Contributing developers
- Using developers
- Quality Assurance

__Next steps__:  
We will reserve time for a first version of the tool and build it.

## Deploy individual components
We first clarified, that we all have the same understanding of this feature:
Biotope developers should be able to publish individual components to a registry to install/use them in a versioned manner.
We decided to add package.jsons to each component, to make it publishable through npm.
Our major challenge here was to find a way to do dependency management. We do not want to bundle everything together.

__Next steps__:  
We will reserve the time, to test out different versions of bundeling and dependency management and will adapt the build to allow a clean dependency mangement.


## Repository setup
We ran into problems maintaing all the single repos. One package worked, but not in combination with other ones. Dependecies were clinching.
Where should a developer start his biotope journey? Where is our main repo.

So we decided to make the CLI our mother repo, rename it to biotope/biotope and put all the genereal documentation there.

## Quality gate: Beginning 21.07.
- add standards which are used by create-react-app
- sync with biotope-boilerplate
- testing in biotope core group
- recheck documentation --> easy guide how to add it
- release 1.0 and share with communtity


Moved to next weekly:
- Biotope Workmode
- Motivate other
- configuration --> biotope boilerplate
- versioned docs
