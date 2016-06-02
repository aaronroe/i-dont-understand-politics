---
layout: post
title:  "Why are most states winner-takes-all for electoral college votes?"
date:   2016-05-30 13:00:32 -0500
categories: post
---
# Answer

[How the Electoral College Became Winner-Take-All][fairvote-how]

* "The shift to statewide winner-take-all was not done for idealistic reasons. Rather, it was the product of partisan pragmatism, as **state leaders wanted to maximize support for their preferred candidate**. Once some states made this calculation, others had to follow, to avoid hurting their side. James Madison's 1823 letter to George Hay, described in my earlier post, explains that few of the constitutional framers anticipated electors being chosen based on winner-take-all rules."
* ![Methods of Choosing Presidential Electors in the First 13 Presidential Elections][systems-over-time]

[Delaware lawsuit challenging winner-take-all state system.][1966-plea]

* "...After the rise of a national two-party system the state unit-vote system became uniform because of the political advantages which accrued to those states which adopted it."

# Pros and cons of winner-takes-all

Pros

* Prevents [gerrymandering][gerrymandering].

Cons

* Can potentially not represent the overall desires of a state, which is ironic because that is exactly why it is prevalent.

# Musings

* (Software-Engineering analogy): I never really thought of it this way, but the electoral college system is basically an interface. If you think of the election process as a software system, the electoral college is an interface that allows each state to write its own implementation. The election system calls the implementation of each state and combines the values to determine the winner. It was this decoupling that made it so appealing to the people ratifying the constitution. 

* Another interesting thought is that it is very possible to write an implementation that uses the popular vote of the state. The only problem with this is that the output of the interface is some mapping/list of small integers where the sum is a fixed number; small integers have a large margin of error when being divided, so it seems that the designers of the interface didn't design the API well ;).

[fairvote-how]: http://www.fairvote.org/how-the-electoral-college-became-winner-take-all
[systems-over-time]: https://d3n8a8pro7vhmx.cloudfront.net/fairvote/pages/2010/attachments/original/1449512778/ResizedImage600396-Early-Elections-Graph.JPG
[1966-plea]: http://archive.fairvote.org/electoral_college/Delaware_Pleading_Part1.pdf
[gerrymandering]: https://en.wikipedia.org/wiki/Gerrymandering