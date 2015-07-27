# Agile Architecture Challenges

Now that I discussed the Agile paradigm and Software Architecture, let's talk about the intersection between the two.

Even while agile methodologies are getting widely accepted in the development world, there is still a lot of debate about how to apply them to the architectural space. One of the most conflictive issues stems around “big design upfront,” which is strongly discouraged by agile practitioners, and the traditional approach to architectural design.

In our original paper from 2010 [^1], Diego Fontdevila and I proposed a set of team dynamics, conceptual practices, and specific technologies to embed software architecture within the agile approach—keeping up the shared goals of technical excellence, streamlined development practices, and a constant and ever- increasing flow of business.

## Architectural Dynamics in Agile Teams

One of the 12 principles of the Agile Manifesto states that “the best architectures, requirements, and designs emerge from self-organizing teams.” We took this to heart —especially, the reference to our shared specialization.

While architecture is an activity that is historically performed with an emphasis on the early stages of a project, the main focus of agile development is on emergent design and iterative production— creating a series of interesting challenges down the road.

First of all, agile makes a big push toward shared responsibility and, thus, dilutes the traditional role of the architect as the one who “defines” the higher-level design of a solution. In this new approach, architecture (as most other development activities) is something that is performed by the whole team -—preserving its multidisciplinary nature. This does not imply that the architect profile goes away, as with all the other roles; it means that while someone contributes with a broader and probably more experienced perspective (usually leading in this aspect), the whole team participates and understands the implications of the design decisions that it makes, and continuously evaluates them.

In our experience, key considerations—such as the modularity strategy, how communication is handled within and outside
the application, and how data and services are accessed and abstracted—are successfully defined and implemented when the whole development team establishes a consensus about these issues. In this way, team members fully understand the consequences of
the selected alternatives, remain aware of their initial assumptions throughout the solution life cycle, and quickly raise concerns when their validity is affected.
Most of these challenges are usually tackled by folding architectural discussion and revision into the regular meetings that take place over the course of an iteration—such as planning and review meetings, and frequent sync-ups and design meetings with plenty of white boarding and open talk. It is also worthwhile to have the most important guidelines permanently exposed in an informative space, including diagrams, checklists or reference charts around the walls, and semipermanent flip charts that are used as posters.
This article does not cover in detail specific techniques that
apply to coordinating several subteams; mainly, it mirrors the standard guidelines about “Scrum of Scrums”. The addition to such activities is a stronger focus on the preservation of conceptual integrity—thus, planning frequent high-level design meetings between teams. Again, these meetings should avoid becoming architect meetings; while the contribution of team members who have a stronger architectural background is obviously important, it is very important for other members to participate. Even the less experienced team members can provide a somewhat naïve perspective to some discussion—promptly flagging complexity excesses that are a professional malady among us architects.

To close on the team dynamics, as the agile perspective goes over the standard view of the development team and extends to customers, operations personnel, and other stakeholders, expectation management is a big deal also for the solution architecture. In the strategy I present in this book there is a strong emphasis on mapping the needs and goals of these actors to the architectural constraints and converting the most important ones into strong metrics to be evaluated.



[^1] Software Architecture in the Agile Life Cycle, by Diego Fontdevila and Martín Salías; published in The Architecture Journal, Issue 23, 2010.
