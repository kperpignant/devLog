This week we spent a lot of time preparing for mock interviews (spoilers didn't go well for me).
We also got new tickets. I was tasked with testing our chosen model (meta llama 3.1).

Let's get the mock interviews out of the way. I was ill prepared. I spent so much time grinding
neetcode problems, but didn't get a single one. Even if I had they probably wouldn't have gone well either tbh.
I also got asked some very basic html web development questions that also didn't go well. Turns out if you don't
practice these things you forget how to do em, who'dve guessed. I think I may be focusing my time on the wrong things.
Really going to need to consider that going forward.

Moving on- I grabbed meta llama off of hugging face and downloaded and ran it locally. It's pretty slow, up to 1:30m
to ask it simple Japanese to English questions. This is because I asked cursor to adjust the parameters to run off of my
CPU instead of my graphics card. I have an AMD Radeon 6950 XT and an i5-13000k processor with 64gb RAM and an nvme SSD. According to cursor it would be better for me to run it off of my CPU so I did. Well it runs, but slowly. Next step should be to test the model on the proper hardware, a VM with n100 graphics clusters. That being said, considering how much that would cost, perhaps its better to just assume that it will perform better.

The translations out of the box are sufficient, the speed will only get better with better hardware, the real thing
to be concerned about, in my opinion is performance at scale and how much that will cost us to support...

El Psy Congroo