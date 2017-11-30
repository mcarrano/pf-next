# Process

This is an outline of the shared steps for building solutions for the web. It
states the essential phases that all development projects have a variant of. Projects may combine and loop some of the phases, but they will still exist in some
capacity.

This is not meant to outline a way of building our library.

This is not a recommendation for a process we should adopt.

The document is meant to be used as a starting point to help everyone
contribute meaningful feedback when we are ready to begin building the system. It
is also meant to help everyone pinpoint how different phases of the process affect
them, and how they affect the others.


```
Discovery
  |- get information about the problem we are trying to solve
  |- communicate information about the problem we are trying to solve
Design
  |- create the initial static design
Develop
  |- write code for the component
  |- verify the code works
Document
  |- Document the design
  |- Documemt the code
Publish and Release
  |- run pre release actions
  |- update the website
  |- distribute the product
```

## Discovery

#### Get Information About The Problem We Are Trying To Solve

Tasks:

- gather requirements across projects/stakeholders
- analyze requirements
- review requirements with stakeholders
- decipher relevant information
- clearly communicate the problem

Definition of Done:
- Feature is consistent with PatternFly goals
- Feature is relevant to PatternFly stakeholders
- Scope, cost, and priority are understood
- A decision has been made to move forward or decline this feature


Concerns:

- inaccurate information
- unusable information
- breaking modularization rules

Deliverables:

- Requirements document

## Design

#### Create The Initial Static Design

Tasks:

- create visual representation (mockups) of a proposed solution
- communicate the visual representation

Definition of Done:

- Design solves the problem that was identified in the requirements
- Design has been reviewed and approved by stakeholders
- Design has been reviewed by developer(s) for feasibility and modularity

Concerns:

- inconsistency with current features or product needs
- breaking modularization rules
- Does not leverage/reuse existing assets to the greatest extent possible

Deliverables:

- Design mockups (wireframes and/or hi-res visualizations)

## Develop

#### Write The Code

Tasks:

- write the code
- write the automated tests
- contribute code to project

Definition of Done:

- Code have been reviewed
- All automated tests pass
- Behavior and appearance are reviewed by designer(s).

Concerns:

- scenarios and states that are unaccounted for
- inconsistent implementations
- breaking modularization rules
- uncommunicated changes
- delays of integration into project

Deliverables:

- Code and related documentation

## Document

Tasks: 

- Write the design documentation (Markdown files) for web site
- Write the code documentation and specs

Definition of Done:
- documentation is complete
- editorial standards have been followed

Concerns:

- Design documentation and code behavior is inconsistent
- Documentation does not meet standards or is inconsistent with other documentation

Deliverables:

- Markdown files
- Others?

## Publish and Release

Tasks:

- Website has been updated
- Release (?) has been built/updated
- Changes and additions are communicated

Definition of Done:

- New feature is available through both the website and GitHub repo
- New feature is communicated to PatternFly community (as applicable)

Concerns:

- New feature breaks the build or website

Deliverables:

- Release notes and/or outward communication (e.g. blog post or other)
