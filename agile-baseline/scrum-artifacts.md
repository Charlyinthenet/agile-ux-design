# Scrum Artifacts

  * 3 main Artifacts:
  * Product Backlog
  * Sprint Backlog
  * Product Increment
 
## Product backlog
Is an ordered list of all the works items that might be done for the product.
It’s the currently best view on the product

Product Backlog Items (PBI) can be:
  * Functionality description
  * Requirements
  * Epics (big Stories)
  * Development pre-requisites
  * “Spikes”
  * Gain technical understanding
  * Known bugs
  * Other work items
  * AND also User Stories(but not exclusively!)
  * ...
But there’s No need to clarify it all upfront!

It is dynamic and constantly changing to identify what the product needs to be appropriate, competitive and useful. As long as a product exists, its Product Backlog also exists.

Only the PO manage the product backlog (everyone can add PBIs but only PO decides on their value).

### Product backlog item PBIs characteristic:
Every:
  * Feature
  * Functionality 
  * Requirement
  * Defect
  * Enhancement
... needed for the product to be robust and valuable.

Its elements have the following attributes: description, order, estimate and value.

Tips:
The Product Backlog, however, could be considered as a "database" with elements
containing the following data:
- Item title
- Description
- Estimate (story point, person days, ...)
- Tentatively schedulable in Sprint
- Dependencies to / from other backlog items [the less dependencies we have, the better!]
This list is, of course, sorted, so each element also has a sequence number.
The Sprint Backlog has a similar format:
- Item title
- Description
- Estimate (story point, person days, ...)
- Dependencies to / from other backlog items [the less dependencies we have, the better!]
In a regulated environment (medical equipment, software involving payments, ...) the backlog often contains elements necessary for tracking how the Item is
implemented: what changes are made, where, ...: in this case the Product Backlog is "crossed" with the version control systems in order to clarify how each
Item.


## Sprint backlog
Is a subset of the product backlog that lists team selected PBIs
Contains items selected from the sprint, plus task specific to the development team
The development team updates the sprint backlog throughout the sprint

## Product increment
Total functionality of all the PBIs delivered and accepted in a sprint

Increment requirements:
  * Team’s definition of Done
  * PO’s acceptance criteria
  * Value envisioned in Sprint Goal
  * Documentation

## Other “non-conventional” artifacts

### User Stories
The User speaks her own business language and has little to no understanding of the technology behind the product she uses. We call this language “Businessish”. The Developers instead speak a technical language, very specialised and well-suited for describing the details of the system being developed. Let’s call this “Geekish”.

#### A metaphor 
When you go to the doctor - do you have to study medicine prior to your visit? No! So how does the interaction work? The patient goes to the doctor and explains the problem in her own language, i.e. her “Businessish”. So between doctor and patient...
- The interaction happens in Businessish, i.e. the doctor needs to learn and understand Businessish
- The doctor needs technical notes in Geekish to be able to provide a therapy
- The diagnosis is just a token representing the discussion, but it cannot replace the discussion

#### User Stories “3Cs”
* Card →
   * “User stories are written on cards. The card does not contain all the information that makes up the requirement. Instead, the card has just enough text to identify the requirement, and to remind everyone what the story is.”
* Conversation →
   * “The requirement itself is communicated from customer to programmers through conversation: an exchange of thoughts, opinions, and feelings. [...] The conversation is largely verbal, but can be supplemented with documents.”

* Confirmation → 
   * “No matter how much discussion or how much documentation we produce, we can’t be as certain as we need to be about what is to be done. The third C in the user story’s key aspects adds confirmation that we sorely need. This component is the acceptance test.”



#### User Story Formats
A way to describe a thing we want to build with the best known - “Connextra template”:
```
As a
I want to
So that
```
Helps discovers different user type… but there are some drawbacks:
Many teams use these templates with their brains switched off: they simply use the template mechanically, but without reasoning on what is behind a story. The results can be bad: 

“User Stories” that are not related to any User of the system 
- “User Stories” that do not describe actual functionality (e.g. refactoring) 
- “User Stories” that are not a good modelling of the system 
- Focus on the form of the story, rather than on the content
The template generates quite some text that needs to be read over and over. This has the following consequences: 
- Everybody spends a lot of time reading 
- The concept behind the story is not immediately clear 
- Everybody loses the “big picture” of the product
- It conveys the impression that the text in the template could be made so “perfect” that we do not need anything else
- The template is used as a feed-forward specification
- There is no communication between Developers and Users anymore
The solution is actually very simple: instead of the template, the visible part of the User Story should be a simple 3-5 words description of what the story is about 

##### Acceptance criteria

Set of conditions that defines the criteria that must be met:
For the product owner to accept the story….
To be considered completed

The format:
```Given that …
When ...
Then …
And …
```


### Epics and Themes
Epic: 
a group of features and functionalities.
Seldom used for a business workflow or process
A piece of work that takes more than one sprint to be built


Themes: group of user stories

### Agile estimates
How hard is to build …? 
Estimates can be defined as:
Abstract units and relative sizing
Translation to calendar days based on actual data


Abstract Units - Relative estimation for Story Points (SP):
* Fibonacci scale
* Ideal days
* T-shirt size


#### The value of estimating
* For the Team 
 * Opportunity for analyses 
* For the Product Owner 
 * Understand where the project might end 
 * Decide on priorities

Tips: There are no measures that * truly * measure the productivity of an agile team. Story points are a subjective measure and, under pressure from management, lead to an effect known as “story point inflation” and other organizational dysfunctions.
These articles are relevant:
- https://www.mountaingoatsoftware.com/blog/how-to-prevent-estimate-inflation
- https://www.industriallogic.com/blog/stop-using-story-points/
- http://brodzinski.com/2015/02/story-points-velocity-the-good-bits.html

Remember: Estimates are not Exactimates!

#### Unbiased estimations
But… Estimations are subject to bias and groupthinking.
Think about a Planning poker benefits (independent, conversation and consensus)

##### Planning Poker is a way to limit bias 
Developers estimate silently 
All play their “card” at the same time 
If they are the same, that’s the estimate 
If not, discuss highest and lowest, go back to 1.
Planning poker - more information http://en.wikipedia.org/wiki/Planning_poker and http://www.mountaingoatsoftware.com/agile/planning-poker 

##### Triangulation
When estimating by Triangulation, a team compares the user story they want to estimate with some previously estimated stories. They then decide if the user story is about the same size, smaller or bigger than the other estimated stories. 
Using Triangulation also has other benefits. Without a good reference system in place, teams sometimes start seeing almost everything as a one, two or three story points. Triangulation may also help the team during planning poker sessions. After each team member has revealed their personal estimate, the team is able to ground their collective estimate by comparing the story with similar work they executed in the past. If there are big discrepancies between the estimates, the team can review past user stories with the same number of story points and see which fits best. Triangulation is a very useful tool that should be in every team's utility belt!

#### Motivation and estimation
Theory X and Theory Y
Created by Douglas McGregor’s work was rooted in motivation theory alongside the works of Abraham Maslow, who created the hierarchy of needs. The two theories proposed by McGregor describe contrasting models of workforce motivation applied by managers. Theory X explains the importance of heightened supervision, external rewards, and penalties, while Theory Y highlights the motivating role of job satisfaction and encourages workers to approach tasks without direct supervision. 
Management use of Theory X and Theory Y can affect employee motivation and productivity in different ways


It’s better to have a little pressure to light the fuse … Tom Demarco ,Timothy Lister in “Peopleware: Productive Projects and Teams”

Estimations are not what you want! 
Pressure on team => Change in the estimates 
Less pressure on Team => More Precision 
Time pressure => Low quality 
Estimate <> Commitment! 
“People under pressure don’t think faster” Tom DeMarco in “Peopleware”

#### Velocity
how many points are accomplished in a sprint?

#### Accuracy VS Precision
Accuracy is closeness of the measurements to a specific value, while precision is the closeness of the measurements to each other.

#### Roadmapping
a classical planning is inaccurate. 
But a roadmap is useful to:
Prioritize
Use timing (near term, mid term and long term)

### Agile prioritization
3 methods:
Assumption testing (remove risk assumption)
Biggest assumption (1-10) + Important score (1-10) = Rank


The BUC method
Business benefit (1-10) + User benefit (1-10) + Cost  (1-10) = Final Score


MOSCOW method
* Must
* Could
* Should
* Would

### Definition of done (DoD)
The definition of done is a checklist that must be completed to allow a feature to be considered completed / done.
What does it mean “story done”?
How “potentially shippable” is your product?

#### DOD - characteristics
* It’s about a Scrum Team agreement
* Needs to improve over time: Teams should regularly review and update the DoD
* Most important: no compromises on quality!

#### DoD Examples: 
Developer has unit tested the functionality
All acceptance criteria has been met
Regression have been completed
Code has been delivered by another developer 
Best practice: add the UATs within the Sprint

##### Definition of Done VS Acceptance Criteria
A feature is finite if:
- meets the generic criteria: definition of Done
- meets the specific criteria: Acceptance criteria

#### Definition of Done and Undone
Goal: Move the Undone in the Sprint! Usually by automating it
