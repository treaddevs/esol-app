# ESOL Communication App

This project was a partnership between the City of Portland, Maine's Office of Economic Opportunity. Adapted from an online tutorial by Coding in Flow, our team developed a central platform for the ESOL Collaborative educators to communicate and share resources.

<a href="/esol-app.pdf" target="_blank" rel="noopener noreferrer">SSD Documentation</a>

**IMPORTANT**: After cloning the repo, open the command line inside the project and run `npm i --legacy-peer-deps`.



Before running the project, you’ll need to create a `.env` file in the root directory and add the following environment variables:

#Vercel Postgres<br>
`POSTGRES_URL=******************************************`<br>
`POSTGRES_URL_NON_POOLING=******************************************`<br>
`POSTGRES_USER=********`<br>
`POSTGRES_HOST=***********************`<br>
`POSTGRES_PASSWORD=***********`<br>
`POSTGRES_DATABASE=******`<br>
`POSTGRES_URL_NO_SSL=*****************************************`<br>
`POSTGRES_PRISMA_URL=*********************************************************`

#UploadThing<br>
`UPLOADTHING_SECRET='***********************************'`<br>
`NEXT_PUBLIC_UPLOADTHING_APP_ID='**********'`

#Stream Chat<br>
`NEXT_PUBLIC_STREAM_KEY='***********'`<br>
`STREAM_SECRET='*******************'`

#Other<br>
`CRON_SECRET='*******************'`

Note: These values are private and must be obtained from your own Vercel, UploadThing, and Stream Chat accounts. Include `.env*` in the .gitignore file so these are not committed to version control.
