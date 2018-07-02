---
layout: post
title:  "Manager's Dilemma"
date:   2018-06-01 18:00:00 +1000
categories: gametheory game theory improvements management
---
#### Why a "little healthy competition" among management peers might not get you the results you expect.

> Notes:
    * Hard to please bosses who seem to use more stick and less carrot,
    * human bias to notice anecdotes over trends

If you've worked for a company which has a layer or two of management there's a good chance you'll have found yourself wondering why everybody can't just work together towards a common goal!? Why does everyday life in an office look so much like a Dilbert comic strip? Apart from humans being imperfect[^1] with a lot of non-rational behaviours there are rational forces at work trying to game the system, sometimes intentionally, but often subconsciously. A darwinian result where those who are good at (office) politics are those who get the promotions, it's a beautiful demonstration of "survival of the fittest" evolutionary theory.

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

## The model

The way Game Theory works is we take two players, in this case Manager A & their peer Manager B, then pick a scenario, figure out what their behaviours could be, then work out the expected pay offs for each party. I've exaggerated the payoffs and simplified it by only considering two players, but apart from getting more complex the theory is still relevant to more real world scenarios.

Some hypothetical payoffs written in English:
1. If both managers cooperate they both get a 20% bonus because their collaboration lead to the company making a bigger profit,
2. If manager 1 cooperates, but manager 2 undermines then manager 2 gets a 15% bonus and manager 1 loses budget for next cycle, loses resources, employees, and political clout,
3. If manager 2 cooperates, but manager 1 undermines then manager 1 gets a 15% bonus and manager 2 loses budget for next cycle, loses resources, employees, and political clout,
4. If both undermine each other the bonuses might go to other managers, but at least they're still on even footing for future promotions.

Payoff matrix for Manager A, B:

|----------------------+----------------------+----------------------|
|                      | Manager A Cooperates | Manager A Undermines |
|----------------------+:--------------------:+:--------------------:|
| Manager B Cooperates |        10, 10        |         15, -50      |
| Manager B Undermines |       -50, 15        |        -10, -10      |
|----------------------+----------------------+----------------------|


This ignores that middle management is not a closed system, new managers may come in and out, there are other players including employers and employees who may impact behaviour.

But that's the point! If upper management change the pay-offs they can shape the behaviours to get more positive cooperative approaches!

Consider if the middle manager's boss punishes negative smeear campaigns, it can make the "Undermine" strategy far less attractive.

Payoff matrix for Manager A, B, where Undermining is punished or at least controlled by "The Boss":

|----------------------+----------------------+----------------------|
|                      | Manager A Cooperates | Manager A Undermines |
|----------------------+:--------------------:+:--------------------:|
| Manager B Cooperates |        10, 10        |          0, -10      |
| Manager B Undermines |       -10,  0        |        -10, -10      |
|----------------------+----------------------+----------------------|


[prisoners-dilemma]: https://en.wikipedia.org/wiki/Prisoner's_dilemma#Strategy_for_the_prisoner's_dilemma
[you-are-not-so-smart]: https://www.goodreads.com/book/show/11709037-you-are-not-so-smart
[wikipedia]: https://simple.wikipedia.org/wiki/Game_theory

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
