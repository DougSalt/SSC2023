See comments below
 
-----Original Message-----
From: ssc2023@easychair.org <ssc2023@easychair.org> 
Sent: Thursday, June 22, 2023 7:44 PM
To: Doug Salt <doug.salt@hutton.ac.uk>
Subject: SSC2023 notification for paper 44
 
[ External email ]
Do not click links or open attachments unless you recognise the sender and know the content is safe
 
Dear Doug Salt
 
unfortunately, your submission to SSC2023 titled "Towards automated provenance collection for experimental runs of agent-based models" received unfavourable reviewer comments. Thus, the submission can only be accepted as a short paper. If this option does not suit you, please retract it and inform us. Otherwise, please have a look at the reviewer comments and update your submission accordingly. You can upload the updated version until July 22nd.
In the mean time we will be working on the program. Please be advised that some tracks had too few submissions and were merged with similar tracks.
We look forward to meeting you in Glasgow in September!
 
Corinna Elsenbroich on behalf of the organizing committee
 
PS do not forget to add the author name(s) and use the correct formatting.
 
SUBMISSION: 44
TITLE: Towards automated provenance collection for experimental runs of agent-based models
 
 
----------------------- REVIEW 1 ---------------------
SUBMISSION: 44
TITLE: Towards automated provenance collection for experimental runs of agent-based models
AUTHORS: Doug Salt, Gary Polhill, Corran Musk, Lorenzo Milazzo, Dawn Parker and Kit Macleod
 
----------- Overall evaluation -----------
SCORE: -1 (weak reject)
----- TEXT:
Overall comments:
The authors present their initial work in designing a provenance system, specifically implemented with their SSREPI. Given the preliminary aspect of the work, I've tried to think of what would be useful for prospective readers to take away.
 
One point could be the results of experiments that were run comparing their previous analyses with the ones facilitated by the provenance system. However, despite the authors stating:
"From a workflow perspective, the main result is that the principal diagrams in that paper were successfully recreated, with the same, albeit not identical, results,"
the reader is not provided any further information. You cut out all my bitching here I may have to put some of it back. Actually just included a sentence saying that the graphs had similar features.
 
Another key contribution could be readily usable code or code to be experimented with. I saw a mention of a public repository, but did not find a link to access it. Yes, because we had to anonymise the paper
 
Yet another contribution could be to show how this provenance system design does seek to satisfy some unique characteristics of ABMs. Despite references to this, I did not see much beyond model stochasticity mentioned. This is addressed in the closing comments to a certain extent, but I have put a few words in the introduction to cover this.
 
The SSREPI Schema and provenance diagrams as presented do not, to me, provide much utility. I would suggest to only present them in the context of specific messages that the authors want to emphasize for the reader. I have done this
 
The article reads like a work in progress that is seeking feedback and suggestions from practitioners. Rude I wonder if it would be more usefully presented as a poster. The provenance graphs that are presented, may also be more effective to demonstrate via a larger poster format. I have tried to make the diagrams more presentable.
 
Some additional points:
pg. 1: "However, since these are workflow tools, the focus is on automation and repeatability rather than provenance, which, if it is included, is as an afterthought."
--> I found this statement to be problematic. Provenance in workflow systems in not a new concept. E.g., this paper from 2011 on the Swift workflow system:
Luiz M.R. Gadelha Jr., Ben Clifford, Marta Mattoso, Michael Wilde, Ian Foster, Provenance management in Swift, Future Generation Computer Systems, Volume 27, Issue 6, 2011, Pages 775-780, ISSN 0167-739X, https://doi.org/10.1016/j.future.2010.05.003. Genuinely had not come across this. I have amended this paragraph to include a reference to this, but this needs a good deal more investigation. I had no idea this framework existed.
 
Throughout the paper I wondered if there was some conflation between random stream control and reproducibility of individual simulation runs, i.e., given a set of inputs and random stream that the simulation would always produce the same results, versus the reproducibility of an overall analysis that comes out of a calibration or other simulation workflow. These are, in my mind, very different topics. If the former (simulation level reproducibility) is not ensured, the latter (analysis level reproducibility) most certainly wouldn't be either, but that is not a novel insight. I am not sure about the purpose of this comment. I think the reviewer is confused by our purpose. I will put in the a new discussion section mentioning that the issues that are raised by the review are a direct consequence of getting the reproducibility of experiments working in the first place. I think the reviewer's comments are cart before horse TBH. I have put this in before future work. Done
 
pg. 3: None of the details in the SSREPI Schema are intelligible. I'd suggest to focus in on the desired takeaways from presenting the figure, and only show those.
 
Additional more minor points:
pg. 5: "folksonomomy" -> "folksonomy" - fixed
 
pg. 6: "producing the diagrams such as those in figures 3, 2, 4 and 5" -> Is there a particular reason why the figures are not referenced sequentially? - fixed - stupid Latex ordering
 
pg. 7: "The Dot language used by Graphviz constitutes a primitive graph database. Indeed there are programs that can transform Dot files into TinkerPop GraphSON format [23, 1]. To generate Figure 4, we used the workflow visualisation Dot file rather than the relational database." -> What is the relevance of the TinkerPop GraphSON format in this statement? - explained. Also was explained in Future Work!!
 
 
----------------------- REVIEW 2 ---------------------
SUBMISSION: 44
TITLE: Towards automated provenance collection for experimental runs of agent-based models
AUTHORS: Doug Salt, Gary Polhill, Corran Musk, Lorenzo Milazzo, Dawn Parker and Kit Macleod
 
----------- Overall evaluation -----------
SCORE: -1 (weak reject)
----- TEXT:
The paper is not well organized, which makes it difficult to follow along and understand what the authors are trying to achieve, or how they are going about it. The text reads more like a tutorial with missing sections/context than a paper.
 
Figures 1 and 5 are unreadable. Figures 2, 3, 4 can be read only at extreme magnification. - fixed for reviewer one anyway.
 
It is not very clear what is being tracked or how (except that scripts are involved). The example on page 7 is nowhere near enough to properly illustrate either the process, the goal or the benefits of the approach. The figures are not very illuminating, even those that can be read.
 
Such a tool would be very useful to the community and I’m looking forward to it, but it needs more work or it needs to be explained better.
 

