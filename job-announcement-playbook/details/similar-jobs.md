---
permalink: job-announcement-playbook/details/similar-jobs/
layout: joa-details
category: similar-jobs
title: Similar jobs
sidenav: similar-jobs
lead: This section gives jobs seekers a way to find other similar jobs.
current-fields: ["Job family (Series)", "Occupations"]
---

This is a new section that attempts to address a specific problem:

Over 50% of all traffic to USAJOBS comes from domains external to USAJOBS and our bounce rate out of job announcements is quite high. In other words, over half of our users come from Google or another outside source directly to a job announcement, view the announcement for an average of 106.5 seconds, and then a majority of those users leave the site entirely.

We observed, over several usability tests, seekers evaluating the job announcement by reading the overview and duties section. By that point in reading the announcement seekers were making a decision to move on or not. Thus given our bounce rate we want to provide navigation to similar jobs in case this job is not an ideal fit for this applicant. Both the series link and occupation buttons take the user to search results that will provide them with other options.

As with all changes we'll monitor the impact of this change using analytics and continued testing with job seekers.

### Job family (Series)

Tells the applicant the job family, or category, that the job belongs to. The codes and titles for the job family are the [OPM Occupational Series](https://www.opm.gov/policy-data-oversight/classification-qualifications/general-schedule-qualification-standards/#url=List-by-Occupational-Series). The job family link directs the user to the search results page where the results are filtered by that series.

#### Required
Yes

### Occupations

Occupations are automatically added by our system. We have mapped many of the Department of Labor's [Standard Occupation Classification (SOC) codes](https://www.bls.gov/soc/) to OPM Occupational Series. We use these SOC codes and titles and use our own search engine to search for those titles in job announcements posted to USAJOBS. Each job announcement is tagged with relevant occupations.

The occupation buttons each show the SOC occupation title and the number of jobs tagged with that occupation. Clicking on the buttons will take the user to the search results page where the results are filtered by that occupation.

#### Note on Mission Critical Occupation tags

We will also be using the Mission Critical Occupation tags in this section to allow users to find similar mission critical jobs. This functionality will be in an upcoming release.
