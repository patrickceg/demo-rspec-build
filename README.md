# Ruby on Rails Build Demo

This repository is for a little build system I am using for an assignment.

## Status

I'm going to try different experiments in Git branches, basically with a
[feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow),
merging anything that I think is stable into main
(so I can always go back to main if I need something that at least works enough as a starting point
for a new experiment), never directly working from main.

## Outline

This section plans out what to build.

Elements asked for the assignment are:

* Various checks of a codebase, which implies

    * I'd need a dependency checker or SBOM
    * Static analysis

* Shell/Groovy/Ruby/Python scripts
* Continuous integration tool
* Containers
* [RSpec](https://rspec.info)

### The Rails Bit

Before making a fancy build system, I'll need to set up some code and a test.

#### Research

##### Folder Structures?

To avoid haphazardly dumping code all over the place, I first check for
recommended structures or folder layouts for a Rails project.

I prompted Github Copilot for example folder layouts, and came across
[Mastodon (social media)](https://github.com/mastodon/mastodon)'s repository
that seems to have the same folder structure as what the AI talked about
when I asked to just give me examples of Rails project structures.

The RSpec project folder structure recommendation is right on their site:

* <https://rspec.info/features/6-0/rspec-rails/directory-structure/>

The general Rails project structure is on Rails's site

* <https://guides.rubyonrails.org/getting_started.html#directory-structure>

The above getting started with Rails guide also mentions that structure is made
for you by following through the guide, so I'll do that.
