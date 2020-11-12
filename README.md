# asanaTakehome
Takehome exercise provided by Asana for Data Science internship. Suggest time for completion: ~3 hours

**Provided Information along with data**: We define an "adopted user" as a user who has logged into the product on three separate days in at least one seven-day period. Because we believe that adopted users are more likely to be successful at using Asana in the long term than those that are not adopted, we want to know what things are likely indicators of future adoption. 
**Objective: With this in mind, we'd like you to identify which factors predict user adoption.**

Additional information:
The data has the following two files:
 
A user file ("takehome_users") with data on 12,000 users who signed up for the product in the last two years. This table includes:
  - **name**: the user's name
  - **object_id**: the user's id
  - **email**: email address
  - **email_domain**: domain of email address, e.g. gmail.com
  - **creation_source**: how they signed up for the product. This takes on one of 5 values:
  - **PERSONAL_PROJECTS**: invited to join another user's personal workspace
  - **GUEST_INVITE**: invited to an organization as a guest (limited permissions)
  - **ORG_INVITE**: invited to an organization (as a full member)
  - **SIGNUP**: signed up via asana.com
  - **SIGNUP_GOOGLE_AUTH**: signed up using Google
  - **Authentication** (using a Google email account for their login id)
  - **creation_time**: when they created their account
  - **last_session_creation_time**: unix timestamp of last login
  - **opted_in_to_mailing_list**: whether they have opted into receiving marketing emails
  - **enabled_for_marketing_drip**: whether they are on the regular marketing email drip
  - **org_id**: the organization (group of users) they belong to
  - **invited_by_user_id**: which user invited them to join (if applicable).
 
  A usage summary file ("takehome_user_engagement") that has a row for each day that a user logged into the product.
 
**Please send us a brief report with your findings, along with any summary tables or graphs that you think will help us better understand them. We will not consider more than 1 page of text and 1 page of supplementary visuals. Please also include all of the code you used to arrive at your results. We will be grading the report and your code. **
 
