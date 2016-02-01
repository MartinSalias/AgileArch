# Architectural Inception

Agile Inception is currently a widely used technique used to create a shared vision among the Development Team and the rest of the stakeholders for a given product. First documented by Jonathan Rasmusson in "The Agile Samurai" (Pragmatic Bookshelf, 2010), it involves 10 activities which can be run in a single workshop, sometimes picking some of them or complementing them with other, depending on the project/product at hand.

I facilitated dozens of these workshops over the years, for organizations ranging from small startups to corporations in different industries, and they have always been key to creating an collaborative context among all involved parties.

In short, the 10 activities I run are:

1. Why are we here? - A check-in round with a twist, were every participants states not only their name and role, but what they understand it is their involvement with the product.
2. Elevator Pitch - The group design a **very** short phrase explaining what the product is, whom its users are, its main features, its competitive advantage and some other relevant detail. As an alternative I can use a Product Vision Board (PVB) instead, depending on the audience.
3. Vision Box - We use a physical box (cereal-type) to design a fictitious box for their product, thinking about it as a retail product (even if its not).
4. In/Out/Maybe - The group creates a simple chart about the very high-level scope of the product, stating what it should have, deciding what it **shouldn't**, and leaving some features in a group to be reconsidered later.
5. Community - This is a diagram about the different groups which need to be involved in the product development, and their different levels of participation, in a visual way.
6. **The Solution** - This is the activity were we talk about the high-level technical decisions we can define up-front to build the product. As some architectural discussion takes place here, I will expand on it later in this section.
7. Fears - We chart all the important risks related to product development and delivery from all the perspectives represented in the workshop such as Technology, Market, Cost, Team, Legal issues, Security and others.
8. Size - Here the group discuss the perceived size of the project from several angles: Team Size, including if the is a need for several teams; estimated duration or deadline, sometimes including an __expected__ release plan.
9. **Trade-Off** - This activity involves prioritizing the main non-functional concerns of the project, debating which ones will take precedence in situations where some design decision targeting one of them conflicts with others. This is the other activity related to architecture strategy, so I will expand on it later in this section, too.
10. How much? - At this point the group makes a __shopping list__ of all the important expected costs, including salaries and fees, hardware and software, services, facilities and anything else that can have an impact in the total cost, and perhaps when or how the cost will impact (initial investment, weekly or monthly, tied to releases, etc). We don't typically try to include the actual cost, but have a clear list to produce an actual budget later.

As you can expect, there is a lot more involved in this workshop, but my goal in this section is to provide you with a general idea and get slightly deeper in the two highlighted activities:

## The Solution

While the technical participants will be leading this activity, the main purpose is for them to clearly explain to the rest of the group several things that they better understand and agree on as soon as possible. For example:

- Types of clients for the application (web, mobile, desktop, APIs, special devices)
- Supported platforms (browsers, desktop or mobile OS, form factors)
- Integration (with services, corporate applications, databases, sensors or networks)
- Dependencies (with other products, projects, technologies)
- Expected behavior for particular scenarios (should the mobile apps support offline usage? are there some kind of distributed transactions? there are some extreme load situations? some critical time-sensitive operations?)

What we try to achieve here is a shared understanding about implementation/architectural details and how they will support the main business requirements. As the group sketches diagrams and talk about the implications of different parts, a lot of assumptions from the different participant areas come to light and new ideas retrofit this early draft of the architecture.

## Trade-Off

The starting point for this activity is to agree on a set of 5 to 8 attributes representing the main non-functional concerns about the product. Most of these are the typical Quality Attributes we use in Software Architecture, but I often let the group add some they find important. For example, I find these in real-life Inceptions I facilitated: Total Cost of Ownership, Time-to-Market, and even Team Life Quality[^1].

As I like to run this, once we agreed on list, I make the group write each one on a sheet of paper (big block letters filling the whole page) and then I make one person for each attribute to hold the paper, showing the name to the others. Then they stand in line, one next to the others, like in a police suspect line (which is a fun moment) and we discuss the relative positions, from left to right (choosing which side means MOST important). The group keeps discussing and swapping the people in the line to reflect the priorities. As a facilitator I help them come up with some potential conflict scenarios between most attribute pairs, so everyone understands they can't make the cake and eat it, too.

Once there is an agreement that the line represent their best bet, I usually ask the people in the line to slightly turn so I can snap a picture of them where faces and signs are clearly seen, in order. I found over time this picture showing what I call the "Quality Strategy" for the product, with faces the actual team members building the product (and most stakeholders) can recognize, is way more powerful to align decisions than any standard document.



[^1] Weirdly enough, the latter was agreed to be the most important issue in that project, as this was the third attempt at solving the same problem, and the pressure had burned the teams on the previous attempts.
