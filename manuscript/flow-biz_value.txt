# Business Value

As we recognize that delivering value early and often is what makes agility attractive to our customers, then we have to be able to justify our technical decisions following the same principle.

In that sense, non-functional requirements should be derived from the same kind of experimentation we use to build the most appropriate product over time, by staying lean and refusing to include features "just in case" some possible event happens.

We strive to make architectural discussion with stakeholders, and the corresponding design decisions and implementation continuous tasks, the same way as analysis, functional design, coding, testing and deployment.

We want to have a **permanent relationship** between stakeholders and architecture (represented by the team, not necessary "architects").

To do this, we have to develop a common language accessible to everyone like other pattern languages. Among other ways to encourage this, I developed over time a deck of cards which finally became the "Architectural Tarot" (you can see the whole deck in Appendix I). The cards provide a visual approach that better engage non-technical stakeholders in architectural discussions.

We do this by using the deck not only during an Agile Inception or other kind of kick-start workshop, but frequently in iteration planning meetings, as we keep finding about the non-functional requirements as we develop the product and start using it.

## Architecture in an Agile development cycle

To better illustrate how architectural discussion gets integrated as part of the expected "osmotic communication" of an agile environment, I will use the Scrum diagram drawn by my friend and colleague Martin Alaimo:

![Scrum](../images/Scrum-Alaimo.png "Scrum - a framework (by @MartinAlaimo)")

Even if you are not following Scrum, this diagram shows  high level view of most iterative flows. Below I list the Scrum names and then the generic description which can apply to any other agile approach.

- Product Backlog - a dynamic list of prioritized work to do
- Sprint - an iteration (usually of fixed lenght)
- Planning - session at the start of each iteration
- Definition of Done - shared agreement on when an item is "Done"
- Review - session to evaluate the product increment at the end of the iteration
- Retrospective - continuous improvement session (usually on every iteration)

How can we mix architectural __stuff__ all over there?

- Planning and Reviews
  While discussing every item with stakeholders, the team can use the Architectural Tarot (or any other technique) to better understand the quality attributes involved.
  Based on the expected behavior, the team might come up with some quality metrics which may become either (a) Acceptance Criteria for this particular item or (b) something to be added to the Definition of Done, as it will be expected on several different contexts.

- Retrospectives
  As part of the focus on improvement, the team can review how the architecture is doing so far, trying to figure out potential problems and spot common excesses on time.
  Some inductive reasoning questions I use for that are:
  . What we feel is too fragile so far?
  . What is being to hard to do?
  . What can we make simpler in our current architecture?

A few recommendations before closing this section:
- Keep architectural ideas coming from the retrospectives on the lookout for next planning
- Beware of polluting the Definition of Done, and remember that anything there should be explained and agreed with the customers/stakeholders
