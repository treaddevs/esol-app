# ESOL Communication App

This project was a partnership with the City of Portland, Maine's Office of Economic Opportunity. It was adapted from an fullstack online tutorial by Coding in Flow. This modern web application is intended to support the city's [ESOL Collaborative](https://www.portlandmaine.gov/1537/ESOL-Collaborative) – to help organization members communicate, share resources, and schedule meetings.

**IMPORTANT**: After cloning the repo, open the command line inside the project and run `npm i --legacy-peer-deps`<br>
// (this addresses release candidate dependencies)

![ESOL App Screenshot](/documentation/esol-home.png)

<a href="/documentation/esol-app.pdf" target="_blank" rel="noopener noreferrer">Software Design Documentation (SDD)</a>

Before running the project, you’ll need to create a `.env` file in the root directory and add the following environment variables:

**\# Vercel Postgres**<br>
`POSTGRES_URL=******************************************`<br>
`POSTGRES_URL_NON_POOLING=******************************************`<br>
`POSTGRES_USER=********`<br>
`POSTGRES_HOST=***********************`<br>
`POSTGRES_PASSWORD=***********`<br>
`POSTGRES_DATABASE=******`<br>
`POSTGRES_URL_NO_SSL=*****************************************`<br>
`POSTGRES_PRISMA_URL=*********************************************************`

**\# UploadThing**<br>
`UPLOADTHING_SECRET='***********************************'`<br>
`NEXT_PUBLIC_UPLOADTHING_APP_ID='**********'`

**\# Stream Chat**<br>
`NEXT_PUBLIC_STREAM_KEY='***********'`<br>
`STREAM_SECRET='*******************'`

**\# Other**<br>
`CRON_SECRET='*******************'`

**NOTE:** These values are *private* and must be obtained from your own Vercel, UploadThing, and Stream Chat accounts. Include `.env*` in the `.gitignore` file so these are not committed to version control.
