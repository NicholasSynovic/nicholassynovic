# Nicholas M. Synovic's GitHub Account

> Computer Science Researcher and Ph.D Student @ Loyola University Chicago

## Table of Contents

- [Nicholas M. Synovic's GitHub Account](#nicholas-m-synovics-github-account)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Repository Scheme](#repository-scheme)

## About

This GitHub page is for my academic, personal, and work repositories.

For more personal information about me, you can visit my homepage
[here](https://nicholassynovic.github.io).

## Repository Scheme

After crossing 100 repositories in April of 2024, I decided to evaluate how I
have been using GitHub. I found that I implement many antipatterns and smells
that make it difficult to work on projects and keep track of work. Because of
this, I've decided to implement the following rules for each of my repositories:

1. Name all projects to follow a standard schema.
   - Much of my time is spent going through my collected repositories trying to
     figure out what each does, how it relates to other projects, or if it is a
     singleton repository. Thus, a naming schema to ensure that *repository
     names* are consistent has to be created and put into place to allow for
     ease of access. A *repository name* is different from the *project name*.
     See point 2 for more information on project names.
   - The schema is as follows: `research|web|tool|prime|final|_project-name`.
     - Archived projects follow `research|web|tool|prime|_project-name_archive`.
     - Part one of the schema defines a general tag for the repository. Part two
       of the schema is the project name of the repository. Part three is
       optional and defines if the repository is archived.
1. *Project names* are always listed in the *project description* and must have
   an acronym. The acronym is always lowercase for ease of typing.
   - Example: `Process Internal Metrics (prime)`
1. Disable as many optional features as possible that allow for collaboration on
   repositories *by default*.
   - This is to reduce the amount of clutter and features that I need to worry
     about *when I start working on a project* and to allow me to enable
     features *as needed*.
1. API docs, regardless of the size or scope of the project, are a must.
1. A `Makefile` must be included and support the following: - `build`: Build
   *and* install the project, - `create-dev`: Create the development environment
   to work on the project, and - `run`: (**Optional**) execute the code
1. A well-written `README.md` file that documents the project and its goals *as
   well as* hosted on GitHub Pages when readily available.
