# BlackBelt
A quick summary of statistical methods used for my Six Sigma Black Belt project
  In 2007, I had finished six sigma training and completed the exam, but was searching for a final project for certification. 
  Some months later, I had the opportunity;
a plant manager (my boss) at an employer claimed that cycle counters under my supervision were miscounting raw materials and WIP inventory in the facility, causing 'lost' inventory on the books.  Cycle counters are people who, usually on 2nd shift, will move around a warehouse and sample count inventory to verify materials accuracy.  The process is tedious, expensive, and at the end of the day, non-value added.    The plant manager also claimed to be able to quantify the loss.    
  So, I had responsibility for the cycle counters under my supervision, as well as financial responsibility for inventory levels.
  How should we test the accuracy of the cycle count folks?   ie. How good were the counters at counting?   We would need to compare a randomized sample of their nightly counts agains some standard.    Luckily, I had at my disposal several "All hands on Deck" 100% physical counts, in which everyone came in during Saturdays, or stopped production during the week for a couple days, and counted and audited everything.  (This happened alot, perhaps once per month, did I tell you this company was obsessed with their inventory accuracy?)  - I'd also counted 45 bins myself.    Armed with these verified counts, I posed an experiment:  directly AFTER a physical audit,  (before inventory could be consumed for production), I would have cycle counters count a random sample of bin locations without telling them the nature or purpose of the selection.   There were three cycle counters, and a team leader who also counted.   Let's see how they did:
 
CONCLUSIONS:
  One-Way ANOVA was performed for each Cycle counter for repeated blind trials - counter vs. the physical audit.  I also audited my own 45 bin counts against the audits.    A sample audit and an ANOVA are attached for interest.
Next, a two-tailed T test was performed on each counter's counts.   The purpose of this simple experiment is to measure and define whether the cycle counters' samples were statistically different from the physical audits (or my 45 bins).  For good measure, I tested my own counts against the audits.
  The result?   With an alpha of .05, the T test (not attached here) showed that their counts were not significantly different than the audited inventory counts.  - My boss was wrong.   
  Though one worker was a bit lower than her peers, all counters counted with an accuracy of 98% or better.   In dollar terms, it did not match the boss's claim of $15,000 inventory 'lost' through inaccuracy per month.
The T test told us we were sampling and counting in the same way.   The boss's claim could not be verified.  
  But where did the loss come from?  We were incurring unacceptable inventory losses.   
  The answer: Conversion from raw materials to WIP to finished goods was not posting properly in the plant accounting system.
-Sometimes the obvious answers are in front of us in plain site, but at least we were able to rule out cycle counting arror as a cause.

  An add-on to this study dealt with root cause analysis of plant scrap and material movement on the floor.  (Analysis not shown, but see "L&P Define&Measure" doc attached.)
This became the basis for my Black Belt Project.  BB granted in April, 2009.
