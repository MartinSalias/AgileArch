# Chapter 1: Agile & Software Architecture

Software development is a pretty new discipline. It started in theory with Charles Babbage and his Differential Engine, and Lady Augusta Ada Byron, Countess of Lovelace, becoming the first programmer in history, although she never had the actual computer to execute her programs!

From these early days to Word War II, computing turned from theory to a mean to push mathemathics to a larger scale, and remained as an academic endeavor until the early 50's, with the Univac. Later that decade IBM starts producing their first commercials computers and programmers start spreading from mathematicians to engineers, and a new species was born: the homo-nerdus, also known as "computer programmer".

Early programming methods were pretty much ad-hoc, and the cycle between coding and compilation could be measured in weeks, from punching the cards (which sometimes the coder could not do on her own) to submitting the batch of cards to the Computer's Administrators and wait days to receive back a paper listing with the result run or just pages of error information.

As computers became popular in the corporate world and software applications got more complex, the need to stronger engineering practices appeared, and from 70's to 90's our industry exported ideas and processes from the previous engineering fields, from electronics to civil construction. The result introduced several problems, basically because programmers got subjected to controls and environments closer to blue-collar workers than designers, most of the time restricting innovation and creativity.

Agile software development crystalized at the start of the XXI century as a reaction to these prescriptive processes, putting the focus back in the non-repetitive side of programming, fostering relationships, team dynamics, collaboration outside of the technical roles, and maximizing feedback loops everywhere.

In the first part of this book I want to provide a short recap of its main topics, just to set expectations, boundaries and terminology I will use in the rest of the book, and as a pivot for further discussion.

First I will review the Agile paradigm from the values and principles and the practices in he most common frameworks like Scrum and Extreme Programming, its Lean __cousin__ Kanban, and then what I understand as the meta-model behind Agile.

Then I will do the same with Software Architecture, focusing mostly in the type of Architecture I will refer to in this book, and pointing to connected disciplines.

Lastly I want to present my view of the main challenges Software Architecture face on Agile teams, projects and organizations, and provide a short overview of the different approaches I present about this topic during the rest of the book.

### Acknowledgements

This book is still a work in progress, but luckily I'm not alone. I want to thank several friends who helped me come to the ideas I'm compiling here, and also the ones helping me during writing, by providing feedback about concepts, grammar even my style and humor (or lack of thereof).

I have to thank first Diego Fontdevila who wrote with me the paper where I started writing down the ideas and experiences I gathered over the previous ten years (Software Architecture in the Agile Life Cycle, Architecture Journal #23).

Several years before the paper, I worked and taught Software Architecture with Diego González and Juan Ladetto, whose insights and ideas were really influential in many of my choices and research.

Also, I feel in debt with Ted Neward, whose book "Effective Enterprise Java" had a huge impact in the way I see the field beyond any technology, and of course, because he started the idea of Architectural Katas, which I later adopted and customized to run in several events and also as part of my workshops.

I also need to thank the whole Southworks crew, in special Johnny Halife, Matias Woloski and my old-time friend Angel "Java" López. I always miss the awesome discussions we had, full of ideas and practical wisdom. Also, I enjoyed working and discussing with the team at Microsoft Patterns & Practices, one of Southworks most important customers, in particular Eugenio Pace and Scott Densmore.

As I joined Kleer and designed my Agile Architecture Workshop, I had great input from several of my colleagues at Kleer, especially Juan Gabardini, Luis Mulato and Yamit Cárdenas, and colleagues from other companies like Raúl de Villa Cano, Marcelo Oks, Andrés Joaquín, Adrián Anacleto, Santiago Blanco and many more I'm probably forgetting.

Lastly, I want to thank the first reviewers of this book, Nico Páez and Scott Baldwin.
