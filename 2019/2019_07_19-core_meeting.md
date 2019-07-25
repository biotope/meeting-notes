# Agenda

1. Biotope-build Update
2. Code structure

## Biotope-build Update
- gulp 4 is set up
- rollup is compiling to es6 and legacy browsers
- deadline is set to October 18th

## Code Structure
- src
  - components/containers/elements/... => folders for all components
  - preview-assets => folder for assets for previewing the components
  - resources => assets used by the components for production
  - services => javascript and typescript stateless functions (app logic)
  - styles => folder for common style (mixins, variables, helpers, ...)
