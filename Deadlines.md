
Begin With the End:
- Provide Deadlines talk: VPs to R&D
- review prioritization process and deadlines treatment on reg basis (VPs reponsibility)

Situation 1:
The Deadline field in YouTrack is used by the requestor to assign the proposed due date. Deadlines come mostly from legal issues, consolidation and onboarding. Currently, we have several issues with the deadline filled in for the team. People within the team are spammed by notifications as the deadline approaches on daily basis. Currently, in most cases, tech people move the deadline towards future in order to avoid being spamming or they just ignore/delete the notifications -> bottom line: the process stopped working.

Quick fix:
1. Axiom: PM (Allison) owns the Deadline field
2. For every incoming issue having the deadline, PM will discuss the date with the requestor and adjusts it accordingly to the team`s capacity and priorities of other issues. PM will review the deadlines on regular basis.
3. For instance, we will use Deadline field only for high-priority issues (eg. regulatory), not legal.


Deadlines: are owned by the team. Only PM can adjust business deadlines.
- update the deadline: regularly or immediately when new facts occur.
- Share deadlines changes and impediments immediately. Ask for help in good time not at the last minute when a deadline is almost up.
- keep access to Deadline field for every requestor, while discussing incoming deadlines as thy show up between Requestor and PM (PM`s responsibility)
- Idea: deadline as year/week num

Priority: my proposal is to use the deadline field in combination with Priority:
- Priority=Minor: is a nice to have request, sholdn`t have deadlines set
- Priority=Default: is a default priority, sholdn`t have deadlines set
- Priority=Critical: used only for issues having deadlines (eg. regulatory, mission-critical, strategic, client features) or those required to be done in next sprint. Note that num of Critical issues should be kept up to ~40%. We can consider to split Critical category into 2: differentiate Soft (roadmap) vs. Hard deadlines (regulatory) due to easier prioritization.
- Priority=Blocker: Issues causing production outage or Issues blocking other teams from moving on with Critical tickets. Occurrence has to be minimal, say 1/Q.

During the sprint planning, the team sorts the backlog by priority desc and deadline asc.

Guardrails metric (Prevention/Team protection):
-	Re-iterate issue type ratio agreement and monitor the ratio on sprint basis
-	Ad-hocs are evil: Monitor the number of incoming ad-hocs. Is ad-hoc form of blocker? Who decides we accept an ad-hoc? Any decision model available? Do we allow only ad-hocs in form of criticals and blockers?
-	Monitor the number of issues with deadlines in the sprint in combination with Overdue issues (passing the deadline)
-	Optionally, monitor the number of postponed deadlines per issue type and priority. Postponing deadlines without communicating reason is pure evil.
- Review metrics on monthly basis with management


--------

Situation 2:
- Rooming list: Critical feature was closed to miss the deadline, even though management pointed to it and was eager to provide help (adding headcount)
- The team was communicating the risk to stakeholders too late
- the only deadline there is 26th March which is long overdue and not communicated to anybody
- even after enquiry about state and offer of help, team didn't ask for it and delivered it 15 minutes before the call
- the delivered product was buggy and lacking basic features (importing new customers)
- Youtrack issue and subissue was absolute MESS. Took me an hour to untagle it, while closing like 6 issues as either completed or invalid or duplicate. Issues were not broken down properly, YT contained partially fixed issues, it wasn't clear at all what was done and what not.

Action: re-iterate Deadlines best practices
https://www.thriveyard.com/20-tips-on-how-to-prioritize-work-and-meet-deadlines/
https://www.quickbase.com/blog/how-to-succeed-when-deadlines-and-priorities-constantly-change

Supporting deadlines:
- priorities
- conducting a postmortem
- notifications for upcoming and overdue deadlines
- followup issues after postmortem dith specific automatic deadline set to 1 mo
- internal deprecation process
