---
permalink: job-announcement-playbook/details/duties/
layout: joa-details
category: details
title: Duties
sidenav: duties
lead: The Duties section lists out the day-to-day responsibilities and activities for the job.  The duties need to help the job seeker understand the type of work they’ll do and help them decide if the job is a good fit for them.
current-fields: ["Summary", "Responsibilities", "Travel Required", "Supervisory status", "Promotion Potential", "Who May Apply"]
previous-fields: ["Relocation Authorized", "Telework eligible"]
---

## Current fields

### Summary

Summarizes what is unique about this job and lists the duties of the job.

The job summary is important to help job seekers understand what is unique about this job and why the job exists.

#### Required
Yes

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__do">
  <h4><span class="fa fa-check"></span> Do</h4>
  * Write a concise one or two sentence summary.
  * Use the position description and job analysis to help write the duties.
  * Use language the job seeker knows and be concise—simpler is better!
  * Avoid internal jargon and acronyms—if an acronym is necessary, spell it out the first time it’s used.
</div>
<div class="usajobs-recruitment-joa-playbook-details__do-not">
  <h4><span class="fa fa-times"></span> Do Not</h4>
  * Do not use the job summary to discussion the mission statement of they agency. This is now captured in the [Agency details](../banner#agency-details).
  * Don’t use dehumanizing terms like “incumbent” or “candidate”.
</div>
</div>

### Responsibilities

Lists the duties the applicant will be expected to perform.

#### Required
Yes

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__do">
  <h4><span class="fa fa-check"></span> Do</h4>
  * Use the position description and job analysis to help write the duties.
  * List each duty as a separate bullet.
  * Describe the day-to-day responsibilities of the job—be specific and include typical projects, resources or technologies that the job will use.
  * Prioritize the duties — put the most important duties first.
  * Use action verbs to start each bullet, such as “Lead”, “Manage”. Refer to the Plainlanguage.gov list of simple words and phrases.
  * Capitalize the first word of each bulleted item.
  * Include punctuation at the end of each bulleted item.
  * Use language the job seeker knows and be concise—simpler is better!
  * Avoid internal jargon and acronyms—if an acronym is necessary, spell it out the first time it’s used.
</div>
<div class="usajobs-recruitment-joa-playbook-details__do-not">
  <h4><span class="fa fa-times"></span> Do Not</h4>
  * Don’t make the duties section overwhelming—a list of 20 duties is too much. Instead prioritize the most important duties.
  * Don’t use dehumanizing terms like “incumbent” or “candidate”.
  * Don’t repeat duties.
</div>
</div>


### Travel Required

This tells the job seeker if the job requires travel.

Options include:

*	Not required
*	Occassional travel
*	25% or less
*	50% or less
*	75% or less
*	76% or greater

[Read more about travel percentages](https://www.usajobs.gov/Help/how-to/search/filters/travel-percentage/).

#### Required
Yes

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__do">
  <h4><span class="fa fa-check"></span> Do</h4>
  * You must enter a value—if the job requires no travel, enter “Not required”.
  * Only enter one value.
  * May include supplemental text to explain the type of travel, such as two weeks of training.  
</div>
</div>


### Supervisory status

This tells the job seeker  if job requires supervising others.

Options include:

*	Yes
*	No

#### Required

Yes

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__do">
  <h4><span class="fa fa-check"></span> Do</h4>
  *	You must enter a value — don’t leave it blank.
</div>
</div>

### Promotion Potential

This tells the job seeker if there’s an opportunity to move up in the grade level.

#### Required
Yes

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__do">
  <h4><span class="fa fa-check"></span> Do</h4>
  * Always enter a value—enter “No” if there is no promotion potential
  * Enter the highest GS level of the potential job promotion.
</div>
<div class="usajobs-recruitment-joa-playbook-details__do-not">
  <h4><span class="fa fa-times"></span> Do Not</h4>
  * Do not repeat this information elsewhere.
</div>
</div>

#### Recent change

With the 6.5 release we moved Promotion Potential out of the [Overview](../overview/) section into Duties. We did this for serveral reasons:

1. We conducted several rounds of card sorting with job seekers. Promotion Potential scored in the bottom half along with announcement and control number which also moved out of the Overview section.
2. It allowed us to reduce the amount of information in the Overview section making the information that remains there more effective (readable and retainable).
3. It allowed us to chunk the Promotion Potential with Supervisory status.

### Who May Apply

Indicates in text who is eligible to apply to this position.

#### Required
Yes

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__do">
  <h4><span class="fa fa-check"></span> Do</h4>
  * Use the terms we have defined to seed the [This job is open to...](../this-job-is-open-to) section.
</div>
<div class="usajobs-recruitment-joa-playbook-details__do-not">
  <h4><span class="fa fa-times"></span> Do Not</h4>
  * Do not include information that is not relevant to eligibility. See the following section for guidance.
</div>
</div>

#### Pre-requisites

The Who May Apply section has contained eligibility information as well as a set of pre-requisites for employment that have found new homes in the job announcement. We've created a set of new fields in our API to collect this information elsewhere. The following is a table showing what information was conveyed in this section in the past and where it should be moved to:

{: .table .table-striped}
| Prerequisite  | Description | New location |
| ------------- | ----------- | ------------ |
| Location - commuting area | Defines the radius of the commuting area | New field in API |
| Location - state | Common with National Guard, i.e. Virginia National Guard, but also some announcements where the applicant has to be within a specific state. | New field in API |
| Cut-off number | When a JOA states it will only accept a certain number of applications | New field in API |
| Second job announcement | When JOA is split between two announcements with different eligibility | New field in API |
| Evergreen | Open-continuous | New field in API |
| Evergreen with cut-off dates | Both open-continuous and having specific cut-off dates | New field in API |
| Agency employees only | Internal posting.  This could be for any agency. | New field in API - New hiring path |
| Reserves | This could be combined with National Guard - National Guard and Reserves | Expand National Guard label |
| In the 1st, 2nd, or 3rd areas of consideration | National Guard | National Guard & Reserves |
| Current high school student | | Education |
| Current graduate student | | 	Education |
| Current graduate student in [field] | A graduate student in a specific field of study. | Education |
| Current student | Is this needed?  Should we offer only specific types?  High school, undergrad, grad, recent grad? | Education |
| Current undergraduate student in [field] | A current undergrad student in a specific field of study | Education |
| Recent graduate only | | Education |
| Recent graduate in [field] | A current graduate student in a specific field of study | Education |
| Non-citizens | A few JOAs mention being open to non-citizens if there are no qualified U.S. citizens | Conditions of Employment |
| Who can't apply | Current Postal service employees not eligible to apply | Conditions of Employment |
| Division only | This is common in National Guard - within certain divisions. But also examples of divisions within an agency (GSA employees within federal acquisition service) | Conditions of Employment |
| Active Military | Should these positions be on USAJOBS? | Conditions of Employment |
| Dual status or non-dual status | This is also related to National Guard - serving on a permanent dual status appointment? Also saw 'non dual status' on some National Guard JOAs | Conditions of Employment |
| PHS commissioned corp personnel | | Conditions of Employment |
| Current intern at agency | Mapped to Federal employees | Conditions of Employment |
| Must attend a recruitment event | | Conditions of Employment |
| Current occupation/job | This comes up in the National Guard.  Looking for current 'technicians' or current 'physicians' | Qualifications |
| Bilingual | Language | Qualifications |
| Can't apply online | These might be excepted service JOAs where you can't apply via USAJOBS, but somewhere else. | The apply URI should point at a page that describes what the applicant needs to do next. |


## Previous fields

### Relocation Authorized

The relocation authorized field has moved to the [locations section](../locations#relocation-expenses-reimbured) and renamed to "Relocation expenses reimbursed". We found in research that seekers were searching for this information when evaluating whether or not they would need to move to apply to this position and thus the Location section was a more logical placement.

### Telework eligible

The Telework eligible field has been given a permanent home in the [locations section](../locations#telework-eligible). We found in research that seekers were searching for this information when considering their commute. We also found that seekers struggled to find the information as it is currently found in 4 sections: Duties, Key requirements, qualifications, and the job title. Giving it a fixed location will help seekers find this information.
