---
layout: post
title:  "Manager's Dilemma"
date:   2018-06-01 18:00:00 +1000
categories: gametheory game theory improvements management
---
#### Why a "little healthy competition" among management peers might not get you the results you expect.

If you've worked for a company which has a layer or two of management there's a good chance you'll have found yourself wondering why everybody can't just work together towards a common goal? Why does everyday life in an office look so much like a Dilbert comic strip? Apart from humans being imperfect[^1] with a lot of irrational behaviours there are also rational reason to try to game the system, sometimes intentionally, but often subconsciously. A darwinian result where those who are good at (office) politics are those who get the promotions, as Netflix say "The actual company values, as opposed to the nice-sounding values, are shown by who gets rewarded, promoted, or let go."

Before we dig in, this blog doesn't require you to know about Game Theory or hold an PhD in maths, but if you'd like to know more watch the movie "A Beautiful Mind" for a vague overview.

## Game Theory?

Quick summary from [Wikipedia Game Theory][wikipedia]:
> Game theory is the study of how and why people make decisions. (Specifically, it is "the study of mathematical models of conflict and cooperation between intelligent rational decision-makers".) It helps people understand parts of science and politics.

The most popular example is the [Prisoner's Dilemma][prisoners-dilemma] which I've used as a basis for this post.

## Competition

The move into middle management typically comes with a reduction in the number of opportunities for advancement, after all, the world has fewer spots for CEOs than it does middle managers! Consider also that bonuses for the management layer will typically come from a set pool of money which must be divided up amongst the management group.

Because of these constraints we'll construct a very basic model where we'll consider middle management as a zero sum game, i.e. middle management is a game which for someone to win, someone else must lose.

## Negative campaigns ftw!

Look to the Netflix TV Series "House of Cards", or any politics around you to see negative campaigns, are some of the most effective tools used, doubly so if you have an audience that only has time or inclination to look at the sound bites, or if you have a paticularly hard boss who considers the carrot as simply an undersized stick!

Negative campaigns are easy to spot, they will typically be media headlines laying bear the seedy parts of politicians private lives, without any real direct reference to ability or qualifications to govern. "They slept with their employee!" not be great attribute for a married politician, but I'm not sure what that has to do with their ability to balance the budget or stimulate the economy. Similar things happen regularly in most work places where managers will say, imply, or highlight the failings of their peers, often with a bit of artistic license or embellishment. When was the last time you saw or heard one of the managers at your work singing the praises of another manager at their level?

Despite how easy negative campaigns are to spot they are incredibly effective, in part due to human's limitations such as the [Cherry Picking bias][cherry-picking-bias] where we are more likely to remember a single interesting anecdote over long term trends of being awesome.

## The Game

The prisoner's dilemma is a standard example of a game analyzed in game theory that shows why two completely rational individuals might not cooperate, even if it appears that it is in their best interests to do so.

For the Manager's Dilemma let's consider Manager A, let's call her Mary, & her peer Manager B, let's call him John, who both work for our fictional company "Big Brick Co". Each year Big Brick Co divides up the profits as bonuses between the managers based on perceived performance. I've simplified real life by only considering two players, but apart from getting more complex the theory is still relevant to the more complex real world scenarios.
1. If both managers cooperate they both get a 10% bonus based on splitting Big Brick Co's profits,
2. If Mary cooperates, but John undermines; then John gets a 15% bonus taking a cut of Mary's share, and Mary loses budget for next cycle, loses resources, employees, and political clout, net payoff for Big Brick Co is -35%,
3. If John cooperates, but Mary undermines; then Mary gets a 15% bonus taking a cut of John's share, and John loses budget for next cycle, loses resources, employees, and political clout, net payoff for Big Brick Co is -35%,
4. If both undermine each other the bonuses might go to other managers, but at least they're still on even footing for future promotions. net payoff for the company is -20%.

Payoff matrix for Mary & John:

|-----------------+-----------------+-----------------|
|                 | Mary Cooperates | Mary Undermines |
|-----------------+:---------------:+:---------------:|
| John Cooperates |  Mary gets 10%  |  Mary gets 15%  |
|                 |  John gets 10%  |  John gets -50% |
| John Undermines |  Mary gets -50% |  Mary gets -20% |
|                 |  John gets 15%  |  John gets -20% |
|-----------------+-----------------+-----------------|

Because undermining a peer offers a greater reward than cooperating with them, all purely rational self-interested managers will betray the other, meaning the only possible outcome for two purely rational manager is for them to betray each other. The interesting part of this result is that pursuing individual reward logically leads both of the managers to undermine when they would get a better reward if they both cooperated.

This ignores that middle management is not a closed system, new managers may come in and out, there are other players including employers and employees who may impact behaviour.

But that's the point! If upper management change the pay-offs they can shape the behaviours to get more positive cooperative approaches!

Consider if the middle manager's boss punishes negative smear campaigns, it can make the "Undermine" strategy far less attractive.

Payoff matrix for Mary, John, where Undermining is punished or at least controlled by "The Boss":
1. If both managers cooperate their collaboration increases efficiences and sales for big company, they both get a 20% bonus based on Big Brick Co's increased profit for a total payoff of 40%,
2. If Mary cooperates, but John undermines; then John loses credibility with their Boss gets a 15% bonus and Mary loses budget for next cycle, loses resources, employees, and political clout, net payoff is -35%,
3. If John cooperates, but Mary undermines; then Mary gets a 15% bonus and John loses budget for next cycle, loses resources, employees, and political clout, net payoff is -35%,
4. If both undermine each other the bonuses might go to other managers, but at least they're still on even footing for future promotions. net payoff for the company is -20%.

|-----------------+-----------------+-----------------|
|                 | Mary Cooperates | Mary Undermines |
|-----------------+:---------------:+:---------------:|
| John Cooperates |  Mary gets 10%  |  Mary gets  0%  |
|                 |  John gets 10%  |  John gets -10% |
| John Undermines |  Mary gets -10% |  Mary gets -15% |
|                 |  John gets  0%  |  John gets -15% |
|-----------------+-----------------+-----------------|

By being more aware of damaging negative behaviour and ensuring that the pay off for undermining is less than cooperating it ensures the only rational behaviour is to work together for the common good.

## Before the whistle

A great write up on how to make what you believe the values of your company become the values of the company, not just fluffy aspirational rubbish Dr. Cameron Sepah has some great pointers on ["Your Company Culture is Who You Hire, Fire, and Promote"][your-company-culture].


[prisoners-dilemma]: https://en.wikipedia.org/wiki/Prisoner's_dilemma#Strategy_for_the_prisoner's_dilemma
[you-are-not-so-smart]: https://www.goodreads.com/book/show/11709037-you-are-not-so-smart
[wikipedia]: https://simple.wikipedia.org/wiki/Game_theory
[cherry-picking-bias]: https://en.wikipedia.org/wiki/Cherry_picking
[your-company-culture]: https://medium.com/s/company-culture/your-companys-culture-is-who-you-hire-fire-and-promote-c69f84902983

[^1]: For a great pop-sci styled book on bias check out David McRaney's "You are not so smart"

<style>
table{
    border-collapse: collapse;
    border-spacing: 0;
    border:2px solid #000000;
}

th{
    border:2px solid #000000;
}

td{
    border:1px solid #000000;
}
</style>
