# Agenda

1. Bio Element "basedOn"-Feature current problems and decision
2. Discuss and decide Biotope-Element "Template PR" by Tiago
3. Biotope Element: Whats missing for 4.0.0 release
4. Versioned documentation
5. Github Actions


## Bio Element "basedOn"-Feature current problems and decision
Since this feature is only partly working in current biotope version and we do only see the two options to remove basedOn feature or switch from wrting Biotope-Element with Typescript to native ES5, we decided to remove this feature with version 4.0

## Discuss and decide Biotope-Element "Template PR" by Tiago
We discussed the pros and cons of this PR. Mainly beeing as much vanilla as possible with Bio-Element vs. "comfort" for developers.
Decission: Create an experimental branch, merge this pr in experimental, release this experimental branch with flag experimental on npm (Tiago)
Afterwards we ll encourage the Biotope community to get their hands on this experimental feature and help us with the decission if it should be a Biotope Element feature or not.

## Biotope Element: Whats missing for 4.0.0 release
Migration guide (Tiago)
Versioned Docs (see next agenda point)

## Versioned documentation
We all agreed that versioned documentation is a must have feature (and a blocker for the final release of Biotope Element 4)
We ll test switching our documentation from docz to Docusaurus because Docusaurus has this feature built in

## Github Actions
We decided to switch everything from Travis to Github Actions.
Github Actions. Responsible persons per repository:
- element, quality-gate (Tiago)
- boilerplate, build, resource-loader (Timo)
- cli, generator, pwa (Marc)

## Not discussed topics due to lack of time
- Commit message standards
- Where to put todos
