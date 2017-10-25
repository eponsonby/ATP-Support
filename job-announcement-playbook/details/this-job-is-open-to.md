---
permalink: job-announcement-playbook/details/this-job-is-open-to/
layout: joa-details
category: this-job-is-open-to
title: This job is open to
sidenav: this-job-is-open-to
lead: This section gives an "at-a-glance" view of who the job is open to.
---

This section is currently driven by the text supplied in the [Who May Apply](../duties#who-may-apply) section. Icons along with their text descriptions will only appear here based on the text that is supplied in **Who May Apply**.

{: .usajobs-recruitment-joa-playbook-details__table}
| Hiring Path                   | Who May Apply content |
| ----------------------------- | --------------------- |
| Open to the Public | U.S. Citizens, Excepted Service |
| Federal Employees| Federal Employees, Current Federal Employees, Former Federal Employees, Merit Promotion, Status Candidates, CTAP, Career Transition Assistance Program, ICTAP, Interagency Career Transition Assistance Program|
| Internal to an Agency| Internal Employee, Agency Employee |
| Veterans | Expanded Veteran Hiring Opportunity,  EVHO, Veterans Recruitment, VRA, VEOA, Veterans Employment Opportunity Act, 30% Disabled |
| Students & Recent Graduates | Recent Graduates, Students, Current Intern |
| Individuals with Disabilities | Schedule A, Individuals with Disabilities |
| Military Spouses | Military Spouses |
| National Guard & Reserves | National Guard |
| Native American | Indian Preference, Native American |
| Peace Corps & Vista | Peace Corps, AmeriCorps, Vista |
| Senior Executive Service | Determined by ES pay plan and minimum salary of $119,000|
| Family of overseas employees | Overseas, Family Member Preference, Eligible Family Member |

If you need to debug why a job announcement is being assigned a hiring path based on the text you provide then you and your Talent Acquisition System (TAS) vendor may find the [full list of valid and invalid text for hiring paths](https://developer.usajobs.gov/General/Hiring-Paths) (production) on our developer site ([UAT](https://developer.uat.usajobs.gov/General/Hiring-Paths)).

**NOTE:** We have established our Hiring Paths as an enumerated list that your Talent Acquisition System (TAS) vendor can use in the future to allow you to select valid options without having to supply the text. The two fields are named "Hiring Path Code" and "Hiring Path Explanation" in our [Data Dictionary](https://developer.usajobs.gov/General/Schemas). Talk to your vendor about this feature. We strongly encourage agencies to switch to using these new fields. String parsing is a temporary solution that allows us to transition to a more structured way of providing and presenting this information to job seekers.

#### Example

This example shows all of the possible hiring paths. No single job would feature all of these.

<div class="usajobs-recruitment-joa-playbook-details__example-img this-job-is-open-to">
<amp-img src="{{ site.baseurl }}/assets/images/job-announcement-playbook/this-job-is-open-to-v6.7.png"
  srcset="{{ site.baseurl }}/assets/images/job-announcement-playbook/this-job-is-open-to-v6.7.png 768w,
  {{ site.baseurl }}/assets/images/job-announcement-playbook/this-job-is-open-to-v6.7-SM.png 100w"
  width="322"
  height="1086"
  layout="responsive"
  alt="This job is open to... v6.7 example"></amp-img>
</div>


### Second announcement

If this job is also open in another announcement to other hiring paths then this section will appear directly below the **This job is open to**. It contains the text "This job is also open in another announcement to" and then lists the other hiring paths. Clicking on this will open a new tab or window, which depends on the preference of the user set in their browser, with the second announcement.

**NOTE:** This is a new field and may not yet be offered by your Talent Acquisition System (TAS). Work with your vendor in order to be able to use this field.
