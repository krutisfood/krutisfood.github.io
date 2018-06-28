---
layout: post
title:  "Manager's Dilemma"
date:   2018-06-01 18:00:00 +1000
categories: gametheory game theory improvements management
---
#### Why a "little healthy competition" among peers in management might not get you the results you expect.

> Notes:
    * Hard to please bosses who seem to use more stick and less carrot,
    * human bias to notice anecdotes over trends

If you've worked as part of a company big enough to have a layer of management or two you'll have found yourself wondering why everybody can't just work together for the common good?! Why does everyday life in an office remind us so much of the Dilbert comic strips. Apart from humans being imperfect[^1] with a lot of non-rational biases there are rational forces at work trying to game the system, often subconsciously. Particularly if you consider those who are good at (office) politics are the ones who get the promotions to fuel the system.

If you don't know what Game Theory is, watch the movie "A Beautiful Mind". But if you don't have time for that, I mean, who does?, Game Theory is a way to explain why actors may behave in a certain way given what their expected reward or punishment would be. One of the most popular examples is the [Prisoner's Dilemma][prisoners-dilemma] which I've based this post on.

The move into middle management typically comes with a reduction in the number of opportunities for advancement, after all the world only needs so many CEOs! Consider with this that bonuses typically come from a set pool of money which must be divided up amongst the group. Given these ideas we'll construct a very basic model where we'll consider middle management as a zero sum game, i.e. middle management is a game which for someone to win, someone else must lose.

Look to the Netflix TV Series "House of Cards", or any politics around you to see negative campaigns, often are some of the most effective tools used.
Negative campaigns are easy to spot, they will typically be about private lives and general character assasination, without any real direct reference to ability or qualifications to govern! "She slept with her secretary" may not be great for a married politician, but I'm not sure what that has to do with her ability to balance the budget or stimulate the economy. Similar things happen regularly in most work places where managers will say, imply, or highlight the failings of their peers, sometimes with a bit of artistic license. Consider, when was the last time you saw one of the managers at your work place praising one of their peers?

Some hypothetical payoffs written in English:
1. If both cooperate they both get a 20% bonus because the company makes a bigger profit,
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
