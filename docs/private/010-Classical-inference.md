# What is classical inference?

Statistical inference is the logic and methods for creating statistical claims that are justified by data. A *statistical claim* is a statement like this: My data show that taking aspirin is associated with a reduction in fever. Or this: My data show that for every year of age, middle-aged runners slow down, on average, by 20-40 seconds per mile.

Statistical inference was invented to guard against spurious claims. For instance, suppose you had these data on age and running times (in minutes) in a 10-mile road race:

Person | Age | Running Time
-------|-----|--------------
John   | 48  | 105
Abigail| 40  | 101

Just comparing the ages and running times of John and Abigail, you can see that John is 4 minutes (that is, 240 seconds) slower than Abigail in completing the 10 mile run. Their age difference is 8 years. This amounts to an additional 30 seconds of running time per year of age difference. (240 / 8 = 30.) Since you are uncertain---this is only one race, this is only two people, etc.---you decide to frame your findings this way: "My data show that middle-aged runners slow down by 20-40 seconds/mile for every year additional age." That is a statistical claim.

There are many problems with this statistical claim. First, it's comparing people who differ in  many ways, not just their 8-year spread in age. In this case, John is a man and Abigail a woman. A different statistical claim, equally  consistent with the data, is that women are faster than men by 30 seconds per mile. Or, it might be that Abigail is an experienced runner and John is running his first race. 

Common sense -- and good statistical practice -- tells you to compare like with like. Wouldn't it be better to compare men of different ages who are both running their first 10-mile race? This would hold constant both experience and sex. Or, how about comparing Abigail's running time this year to her  running times in previous years? Failing to design the study to compare like with like is reason enough to be skeptical about the 20-40 seconds/mile per year claim. But flaws in study design, however grevious, are not what statistical inference deals with.

Statistical inference deals with one, and only one, source of uncertainty: that produced by the size of the sample, in this case 2 people. Again, common sense tells you that two is not a lot of data. So, how much would be enough? 10? 100? 1000? Or, put another way, how should you frame the uncertainty in your claim due to limited data? In the example, the 20-40 seconds/mile per year interval was made up to create an impression of scientific precision. Statistical inference techniques create meaningful intervals that stem from the data itself, rather than the imagination of the researcher. 

The need for statistical inference became important when it was realized, around 1900, that there was not yet a reliable way of knowing how much data---that is, how many rows of data---is sufficient. The founders of statistical inference found ways to frame the problem in terms of the mathematics of probability and employed algebra and other mathematical techniques to solve the problem. They summarized the process of statistical inference using formulas and tables of probabilities. This is *classical* inference.

Algebra and other mathematical arguments can be difficult and subtle. In the early days of classical inference, there were disagreements about what formulas were appropriate. To develop ideas and confirm that their formulas gave reasonable results, some of the founders of classical inference used *simulations*. One simulation, for instance, involved writing down data for 3000 individual people on index cards, shuffling the cards, then dealing out hands of 4 cards each. With 1000 such events, it was straightforward---but extremely tedious---to see which results were likely and which not.

The algebraic techniques were pretty much the only way to conduct statistical inference until the 1970s. Then, as computing became available at research institutions, the simulation technique became easy enough to be practical for routine problems in statistical inference. Simulation on computers became a potent substitute for algebra. The simulation approach to statistical inference has been called *computer-age statistical inference* to distinguish it from *classical statistical inference*.

## ... and why should I read this book? {-}

We live in the computer age, so you might suppose that statistics courses would use computer-age statistical inference. But by and large they do not. There is one good reason and several bad reasons for this. And these reasons -- good and bad -- determine whether you should read this book.

Classical inference is the only way to conduct statistical inference for very small data, say with 10 or fewer rows of data. So if you are working with small data, you need  classical inference.

Putting aside the matter of small data, instructors use classical inference because that is what they were taught. They don't use simulation for a variety of reasons: they may not know about the computer-age techniques, they may not be comfortable teaching how to use a computer, they may see algebra as prestigious and computing as low-class, they may think their students don't have access to computing (and in some places, this might be true), they may have been forced to use the n^th^ edition of a textbook originally written before computer-age inference was accessible and which continues to use classical inference to retain established clients. 

If you going to study classical inference, you might as well study it concisely. Traditional statistics textbooks introduce many ways of summarizing data---means here, proportions there, slopes in another place, correlation coefficients still elsewhere. But these seemingly diverse elements are merely different perspectives on a common theme: fitting a statistical model to data. Putting statistical models at the center of inference streamlines and simplifies the logic. And, rather than laboring over unnecessarily detailed tables of probability, it's better to focus on the essential ambiguities of inference: covariation, multiple testing, researcher degrees of freedom, publication bias, etc.




