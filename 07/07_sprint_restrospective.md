The Sprint Retrospective is an opportunity for the Scrum Team to inspect itself and create a plan for improvements to be enacted during the next Sprint.

The Sprint Retrospective occurs after the Sprint Review and prior to the next Sprint Planning. This is at most a three-hour meeting for one-month Sprints. For shorter Sprints, the event is usually shorter. The Scrum Master ensures that the event takes place and that attendants understand its purpose.

The Scrum Master ensures that the meeting is positive and productive. The Scrum Master teaches all to keep it within the time-box. The Scrum Master participates as a peer team member in the meeting from the accountability over the Scrum process.

The purpose of the Sprint Retrospective is to:

    - Inspect how the last Sprint went with regards to people, relationships, process, and tools;
    - Identify and order the major items that went well and potential improvements; and
    - Create a plan for implementing improvements to the way the Scrum Team does its work.

The Scrum Master encourages the Scrum Team to improve, within the Scrum process framework, its development process and practices to make it more effective and enjoyable for the next Sprint. During each Sprint Retrospective, the Scrum Team plans ways to increase product quality by improving work processes or adapting the definition of “Done”, if appropriate and not in conflict with product or organizational standards.

By the end of the Sprint Retrospective, the Scrum Team should have identified improvements that it will implement in the next Sprint. Implementing these improvements in the next Sprint is the adaptation to the inspection of the Scrum Team itself. Although improvements may be implemented at any time, the Sprint Retrospective provides a formal opportunity to focus on inspection and adaptation.

Further information

When something goes wrong, we naturally search for an explanation or a reason why. Knowing why something happens makes us feel better and helps us put a process in place to make sure this doesn't happen again, or to us. This process goes by multiple names:

    - Root cause analysis
    - Post-mortem
    - Lessons learned
    - Post-incident review

Post-Mortem

A post-mortem is a process to identify a chronological timeline of the events preceding the incident. The intention is to determine what happened and put processes in place to prevent a similar incident from happening again.

    Even if it is called a blameless post-mortem, the process itself is built to identify the cause of the problem.

Root Cause Analysis

Root cause analysis is often included as part of a post-mortem. It's designed to identify the primary reason why an incident occurred.
The definitions of post-mortem and root cause analysis are focused on finding reasons why an incident occurred and preventing incidents from happening in the future. The challenge with post-mortems and root cause analyses is the desire to attribute an incident to a single issue or person. Even if it is called a blameless post-mortem, the process itself is built to identify the cause of the problem. Oftentimes there is never a single cause, rather a combination of events aligned in a certain way contributing to the incident.
Instead of focusing solely on why something occurred and what we can do to prevent similar events from happening in the future, we should strive to focus on what was learned from the incident. Instead of conducting a post-mortem or root cause analysis, hold a lessons learned or post-incident review.

Lessons Learned

Rooted in project management, lessons learned is a formal process of reviewing a project (or incident) and documenting what was learned during it. For incident reviews, this can include a review of how effective the incident handling process was and identifying what needs to be improved or changed. Learning from the experience of others is more valuable than trying to not get blamed for a mistake. If all we are doing is identifying what went wrong and not learning from the incident, we will end up making the same mistakes.

Post-Incident Review

This year saw a trend in IT moving toward a new conceptof post-incident reviews as opposed to root cause analysis and post-mortems. Post-incident reviews put the focus on what can be learned from outages, incidents, and failures. The goal of a post-incident review is to examine the timeline to determine what happened and whether it was handled correctly. The outcome of this is to develop better processes and strategies for future incidents.

Key Components of Any Incident Review

Detection

The amount of time it takes to detect an incident depends on the tools and processes in place. If an organization or team is suffering from alert fatigue, it is possible that alerts are ignored, which results in longer detection. If the proper monitoring and alerts are not configured, customers may be detecting issues before the company knows something is wrong.

Questions to consider:

    - How was the incident detected?
    - How do processes and tools need to change to detect incidents earlier?

Notification

Receiving an alert during the detection phase is part of a notification. Oftentimes there are other stakeholders that need to be notified both inside and outside of the organization. Part of the incident review for notifications should include any relevant social media communications that occurred during the incident. Notifying customers and maintaining communication can help improve a company's reputation when services are unavailable.
Questions to consider:

    - How were relevant parties notified of the incident?
    - How do notification procedures need to change for more effective/timely notifications?
    - How were social media relations handled?
    - How do social media communications need to change?

Assessment

For triage and communication processes, incidents often need to be categorized in terms of severity. Not every incident requires an external notification or social media strategy. Assessing and tracking the severity of an incident can result in different protocols being implemented.

Questions to consider:

    - How was the severity of the incident assessed?
    - How did the severity change through the course of the incident?

Resolution

Sometimes a fix is easy to determine, sometimes it takes a while to determine what needs to be fixed, and oftentimes there is a lot of trial and error. Understanding the dynamics involved in the resolution can identify areas to improve and reduce the overall mean time to repair.

Questions to consider:

    - How was it determined what changes were needed to resolve the incident?
    - How do resolution processes need to change?

It is important to phrase the question in open and non-accusatory ways. Notice the difference between asking "How was the severity of the incident assessed?" and "How do assessment procedures need to change in the future for more accurate assessments?" and "Was the severity of the incident assessed correctly from the beginning?" The latter implies blame, if the incident did not receive an accurate severity level then somebody or something is to blame. Asking a "How?" question instead makes people pause and problem solve instead of trying to assign blame. The answer to how does something need to change, can be "It doesn't." If everything ran smoothly, then nothing needs to change.

    Notice the difference between asking "How was the severity of the incident assessed?" and "How do assessment procedures need to change in the future for more accurate assessments?" and "Was the severity of the incident assessed correctly from the beginning?"

The Human Factor

All the tools and processes put in place are meaningless unless they are designed with a focus on the people. This doesn't mean we look to assign blame to a person or attribute an incident to human error, but rather we look at how people are interacting with the tools and their frame of mind. Understand the perspective, bias, and motivation of everybody involved.
The implementation of blameless post-mortems took people into account. People want to avoid blame. The idea that somebody was to blame creates fear and anxiety. "Will I be fired?" "Will I lose the promotion I was hoping for?" Understand that when people are in a positive frame of mind they are more likely to collaborate and provide truthful answers when problem solving.
We have turned to automation as an attempt to eliminate the chances of human error causing incidents. However, we still see major incidents occurring because we are not considering the humans involved in the processes we are implementing. We like to think that we are rational beings that use logic to make decisions, but our decisions are driven by emotion. According to Chris Voss in Never Split the Difference: Negotiating As If Your Life Depended On It, "While we use logic to reason ourselves toward a decision the actual decision making is governed by emotion."
When we are building software, automating tasks, or developing processes we have to think about the humans involved:

    - When will they be using this? If the process or tool is used during incidents, there is additional pressure and stress during this time. Given that emotions drive decisions, what can be done to lessen the emotions or reduce pressure?
    - If the user is woken up in the middle of the night, how can I make it easier for them to quickly take the necessary actions? Can additional information be included in alerts to help with diagnosing a problem?
    - Is information in protocols and processes conveyed in the simplest way possible, can it be understood by both junior and senior employees at 2 AM?
    - What can potentially go wrong?

Technical solutions that automate tasks are good, but there is a human behind the automation tasks. We need human and technical solutions to help us resolve incidents and have to be willing to acknowledge when a process is broken or we didn't have the appropriate safeguards in place. Strive to avoid the blame or pinning an incident on a human error, unless that error is "we didn't have the right safeguards in place," or "we don't understand the myriad ways our systems can potentially fail."

Example

What did we do well?

    - New Teamsetup was relatively painless and work proceeded as it did before.
    - We started to translate comments and coding from german to english for expert.jar
    - As a new guy on the team, it was possible to get started relatively quickly and felt very welcome
    - Feature Development went well forward

What should we have done better?

    - Not everybody was present during Team Daily (BE)
    - MD is currently not discussed in SoS, because we do not have a representative
    - As a new guy, account creation just starts on the day of arrival, that seemed a bit late.
    - It is not clear today how a new person can share best practices or knowledge from previous teams to the wider team
    - The FE team took up too view stories (at the same time there were topics blocked and it was not possible to proceed)
    - It is not transparent for QA, what is part of a specific release (eg. service released, but not clear what is new)
    - For L2 Team it is not transparent what is availably newly on PROD (Changelog)
