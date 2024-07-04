### Project Info
Glasshouse
Video conference app accessible in-browser on PC and mobile devices
Harrison Pursley

### Tech Stack
NextJS
TypeScript
Clerk
Getstream
Shadcn
TailwindCSS

Created in VSCode
Deployed with Heroku

### API Documentation of Routes
/: home screen
/upcoming: upcoming meetings page
/previous: meeting history
/recordings: videos of recorded meetings
/personal-room: private room
/sign-in: Clerk Sign-in page
/sign-up: Clerk Sign-up page

### Credit
Zoom clone idea and code tutorial lion share: JavascriptMastery on Youtube "Build and Deploy a Full-Stack Video Conferencing App with Next JS"
https://youtu.be/R8CIO1DZ2b8?si=C2YcZ6vyNSeaoEUV
although fixes were needed from various sources

With snippets from Clerk's quickstart NodeJS
https://clerk.com/docs

### Future Goals/Plans
The system I used for user accounts is high-quality but limits scope, so in the event that this app exceeds 10,000 users, I will have to upgrade to a higher-level plan or change providers entirely

### Other Notes
I initially wanted to deploy to Heroku but I found Vercel's deployment system much less frustrating

### Bugs
Date and Time are 7 hours ahead of current and do not refresh in real-time