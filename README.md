# CSS Guidelines

## What is it?
Let me just start by saying that CSS is a bitch.

This is a set of guidelines inspired (shamelessly copied & blissfully extended) from the likes of [SMACSS](http://smacss.com/), [OOCSS](http://oocss.org), [BEM](http://bem.info/method) and others ([https://github.com/team-sass/sucks](https://github.com/team-sass/sucks/)) to be in context with our product development excercises here at Srijan. Though meant for use by any web-development project, the following is biased towards improving and documenting the practices that we currently have adopted. So take what you need and leave what you don't. That's why it's called 'Guidelines' (Duh!).

## Organization
Every project needs some organization. Throwing every new style you create onto the end of a single file would make finding things more difficult and would be very confusing for anybody else working on the project. By categorizing CSS rules, we begin to see patterns and can define better practices around each of these patterns.

There are five types of categories:
1.	Base
2.	Layout
3.	Module
4.	State
5.	Theme