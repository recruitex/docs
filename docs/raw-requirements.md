# TLDR

The system is open-source self-hosted recruitment platform for companies. It allows seamless recruitment process from both ends - recruiter and recruitee.
It should help determine the best candidates for the job and help the candidates find the best job for them. After finished process, the candidate has a chance to rate the company and the recruiters. These ratings, after anonymization, are available for other candidates to see.

# Longer description of requirements

The system aims to provide full recruitment process for companies. From the company's perspective, it should allow to create job offers, manage candidates, schedule interviews, and rate the candidates. Each recruitment process consists of several steps, forming a flow. Steps can be customized by the company. Available steps are: HR interview, technical interview, live-coding task, homework and result. Each step can have assigned questions, that we can ask the candidate. During the very step, the questions are randomly selected from the pool of questions. The company can also define the weight of each step in the final evaluation. The pools can be both public and private. Both live-coding task and homework, should be possible to be done within editor on a page. Homework task should have test suits to be run to verify basic correctness of the solution. The company can also define the time limit for the task (both by dates and by total session length possible). Counter should stop when the page is not focused, we don't want to track people's time when they are not working on the task. Companies should have a comparison view of max 5 candidates. System provides automatic basic review, using AI model, from the notes left by the recruiters. This feature is hidden behind paywall. After providing feedback for the candidate, he can rate the process and recruiters involved into it. After anonymisation, the review is being posted on the public wall of the company. On the company's page we can see the average rating of the company and the recruiters. Companies can leave comments below the ratings, and can ask for a removal of highly improper ratings, but not construcively critique ones. Removal is done manually by moderators. System allows for data processing for future recruitments, if agreed upon. System sends a notification if the candidates profile, matches new openings in a given company. After the recruitment, personal information is removed, and only statistical information remain.