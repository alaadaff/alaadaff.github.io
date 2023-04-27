
We thank the reviewers for their thorough feedback and comments. We discuss larger concerns below, and we’ll address other minor concerns/suggestions in the next version of the paper.

#Consent (Reviewer-C)

The IPV clinic asks for verbal consent to record consultations and that these recordings be used for training and research purposes. Consent is verbal to protect privacy and safety of participants. All volunteers in the clinic complete human subjects research training and are considered part of the research team. 


#Transcript selection (Reviewers-A,B)

We’ll clarify the method used for selecting transcripts and ensure consistent terminology.  Briefly, we used keyword search on all available transcripts in the CMS (232 transcripts involving 200 clients covering May2018 to June2022). Keywords were selected based on author's experience and after reviewing account security interfaces (ASIs) on some services. 

We manually reviewed search results to prune out false positives (transcripts that didn’t involve discussion of ASIs); this reduced to 96 transcripts. We randomly sampled 20% of these to initiate a coding scheme. We then re-examined the 96 transcripts to see which services are covered. We found a total of six services in our data. For two of the services there was only one transcript each; we excluded these. We selected the first five matches for transcripts for each of the remaining four services from the 94 transcripts left resulting in 20 transcripts.

Finally, we wanted to add focus on 2FA, that our initial search keywords didn't consider. Therefore, we used the second set of keywords in Figure 8 to find transcripts with 2FA discussion. We included the first two transcripts found for each service resulting in 28 transcripts. This final set pertained to 22 clients supported by 19 consultants. We believe that this transcript set is sufficient to highlight challenges that clients face with ASIs in IPV contexts. 


#Quantitative data & quotes (Reviewer-B)

We avoided quantitative presentation of our transcript data, since we don’t believe our qualitative methods support statistics that generalize. We’ll also revise to consider Reviewer-B’s suggestion about indicating when a discussion was initiated by a client or consultant.


Novelty, impact of attacks & disclosure (Reviewers-C,D,E)

Yes, the vulnerabilities underlying our spoofing attacks have been discussed in prior work (as we cite in Section(1)), but their impact on ASIs hasn’t been previously discussed in the literature. We’ll improve discussion about the impact of attacks in Section(6). 

Relatedly, we’ll clarify further the behavior and role of different interfaces. For example, 
how an at-risk user would benefit from a log of terminated sessions on Facebook (similar to what Google currently provides) and clarify Google’s interface behavior with respect to hiding attacks.

We disclosed our findings to all four services and three of the services confirmed our results. We’re still waiting to hear back from one service. We’ll include any feedback that we receive in the paper. 


#Better approaches/solutions (Reviewer-D, E)

We discuss approaches and solutions in Section(6). These include improving UI navigation flows, providing detailed lists and activity logs, and improving on the modern web authentication architecture to improve device identification. The latter represents an open problem that we don’t yet have solutions for as it requires balancing with the need to prevent device tracking by services. We leave doing so to future work.

#Reorganization, more services (Reviewer-E)

We consider four services in this work because these are the most common services used by clients at the clinic. These also represent the state of the art in ASIs. Our results would be similar for other services, or worse: most other services have less detailed ASIs. 
In this work we analyze transcripts of consultations conducted over a four year period. The time lag means that there’s no way to accurately map a consultation to a known version of the interface. Thus our dataset doesn’t allow reflecting on the user's experience with specific affordances, and we’ll clarify this limitation in the paper. 

We appreciate suggestions on trimming down background and providing more description of existing ASIs, which we’ll do. Despite the limitation above, we’ll work to tie qualitative results to existing ASIs.  

We briefly mention email based notifications in Sections(1), (2), and (6), but we'll improve our discussion based on the feedback and indicate quotes are modified for anonymization. 




