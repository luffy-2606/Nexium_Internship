# Nexium Internship

## About
I got to know abut [Nexium](https://www.nexium.ltd) through LinkedIn. A random person had shared their post for their AI-enhanced Web Development internship program. 
Not thinking much, I applied here as it just required filling a Form. Later I recieved a email of acceptance and was added to a Google Classroom. All further communications were further done from here.

## Work
There was no actual mentoring that was provided by the Nexium Team. Just a link was shared to us that led to their website, containing 30 YouTube videos with some instructions. The link to this page was: https://www.nexium.ltd/Bootcamp/Student-Handbook (it might be changed/moved/removed later on). 
_The videos and instructions they gave there are mentioned all mentioned down below._

# Here are the given instructions and materials

## Before You Begin Instructions
- GitHub repo: Create a new public repo named Nexium_<yourname>_TaskName.
- Node.js: Install Node LTS ≥ 20 & pnpm.
corepack enable && corepack prepare pnpm@latest --activate
- Editor: Use VS Code with ESLint, Prettier, Tailwind CSS IntelliSense, Prisma.
- DB access: Set up Supabase (Postgres) & MongoDB Atlas. Create nexium-pg & nexium-mongo.
- Hosting: Create a Vercel account via GitHub login.
- Automation: Create a free n8n.cloud account or install locally.
- Add a .env.example with placeholders for secrets.

## Working Rules
-Push updates daily before 11:59 PM PKT.
- Use conventional commit messages (feat:, fix:).
- Work in main or short-lived feature branches.
- All code/assets in /internship folder.
- Submit GitHub links via Classroom before deadlines.
- Maintain ≥ 90% attendance in Classroom.

### 📅 Programme Road-Map

| Phase                | Dates       | Focus                                               | Checkpoint                          |
|----------------------|-------------|------------------------------------------------------|--------------------------------------|
| Foundation           | July 1–7    | Next.js 15, ShadCN UI, DaisyUI, Git workflow        | Assignment 1 demo (July 7)           |
| Automation & Data    | July 8–14   | n8n, AI agents, Postgres, MongoDB, CI/CD            | Assignment 2 demo (July 14)          |
| Grand Project Sprint | July 15–29  | End-to-end build                                    | MVP milestones & beta                |
| Demo Day             | July 30     | Final presentation & review                         | Certification                        |


## Assignments

### Assignment 1: Quote Generator Web App
- ShadCN UI form to enter a topic.
- Displays 3 quotes from local JSON/array.
 -Deployed to Vercel.
- Code in assignment-1/.

### Assignment 2: Blog Summariser
- Input: Blog URL → scrape text.
- Simulate AI summary (static logic).
- Translate to Urdu (JS dictionary).
- Save summary in Supabase; full text in MongoDB.
- Use ShadCN UI & deploy to Vercel.
- Code in assignment-2/.

### Grand Project: AI-Powered Web App
Project Title: AI-Powered Web App
- Auth with magic link (email login)
- AI feature via n8n logic
- Supabase + MongoDB
- Deployed with CI/CD on Vercel

**Choose one:**
1. Resume Tailor
2. Recipe Generator
3. Mental Health Tracker
4. Pitch Writer

| Milestone             | Date   | Push to                 |
|-----------------------|--------|--------------------------|
| PRD + wireframes      | Day 15 | /grand-project/docs/     |
| Backend & DB setup    | Day 18 | /grand-project/api/      |
| Frontend UI           | Day 21 | /grand-project/app/      |
| AI logic + testing    | Day 24 | /grand-project/ai/       |
| Public demo live      | Day 27 | —                        |
| Docs + Loom walkthrough | Day 29 | README.md              |


## Submission & Grading
| Category | Weightage |
|----------|----------|
| Assignment 1 | 25% |
| Assignment 2 | 35% |
| Grand Project | 40% |

- Minimum 85% score overall
- Demo on Day 30
- ≥ 90% attendance

## Support and Communication
- Classroom & email for official updates
- Mentor hours: Mon & Thu, 7–8 PM PKT on Google Meet
- Tag mentors in GitHub Issues for help


# Daily Tasks (30-Day Roadmap)
### Day 1: Kick-off: Repo setup & Git workflow  
Get started by creating your GitHub repo, setting up Node.js and pnpm, and following the onboarding checklist.  
_Deliverable: Repo created, onboarding complete_  

### Day 2: [Next.js 15 Fundamentals](https://youtu.be/6jfgz5VcpC4)  
Learn the basics of Next.js 15, including project structure, routing, and core concepts.  
_Next.js 15 Fundamentals – Watch the video and follow along for hands-on mastery._  

### Day 3: [App Router & Server Components](https://youtu.be/dMCSiA5gzkU)  
Deep dive into the App Router and how to use Server Components for scalable apps.  
_App Router & Server Components – Watch the video and follow along for hands-on mastery._  

### Day 4: [ShadCN UI Setup & Theming](https://youtu.be/V1r0ed0q1F4) 
Integrate ShadCN UI, customize themes, and build reusable components.  
_ShadCN UI Setup & Theming – Watch the video and follow along for hands-on mastery._  

### Day 5: [DaisyUI & Tailwind Styling](https://youtu.be/PctfrkRo8Fg)  
Enhance your UI with DaisyUI and advanced Tailwind CSS techniques.  
_DaisyUI & Tailwind Styling – Watch the video and follow along for hands-on mastery._  

### Day 6: [Accessibility Testing with Lighthouse](https://youtu.be/R1uqNegy8Y4)  
Test and improve your app’s accessibility using Lighthouse and best practices.  
_Accessibility Testing with Lighthouse – Watch the video and follow along for hands-on mastery._  

### Day 7: Peer Review & Assignment 1 Demo (Quote Generator)
Present your Quote Generator, get feedback, and review peers’ work.  
_Deliverable: Assignment 1 demo_  

### Day 8: [Intro to n8n & Webhooks](https://youtu.be/y_cpFMF1pzk)  
Automate workflows using n8n and learn about webhooks integration.  
_Intro to n8n & Webhooks – Watch the video and follow along for hands-on mastery._  

### Day 9: [LLM Flows & AI Agents in n8n](https://youtu.be/o2Pubq36Pao)  
Build AI-powered flows and agents using n8n’s LLM integrations.  
_LLM Flows & AI Agents in n8n – Watch the video and follow along for hands-on mastery._  

### Day 10: [PostgreSQL + Prisma Integration](https://youtu.be/KoX6Ei4CcXY) 
Connect your app to PostgreSQL using Prisma ORM for robust data management.  
_PostgreSQL + Prisma Integration – Watch the video and follow along for hands-on mastery._  

### Day 11: [MongoDB + Mongoose CRUD](https://youtu.be/o1D6rGlKx_c)  
Implement CRUD operations with MongoDB and Mongoose in your backend.  
_MongoDB + Mongoose CRUD – Watch the video and follow along for hands-on mastery._  

### Day 12: [Vercel CI/CD + GitHub Actions](https://youtu.be/gIHBVpJhmEk)  
Set up CI/CD pipelines with Vercel and automate deployments using GitHub Actions.  
_Vercel CI/CD + GitHub Actions – Watch the video and follow along for hands-on mastery._  

### Day 13: Peer Review & Assignment 2 Demo (Blog Summariser)  
Showcase your Blog Summariser, exchange feedback, and learn from others.  
_Deliverable: Assignment 2 demo_  

### Day 14: Assignment 2 Due  
Submit your deployed Blog Summariser for review.  
_Deliverable: Blog Summariser deployed to Vercel (assignment-2/)_  

### Day 15: Grand Project Sprint Begins (PRD + wireframes)  
Kick off your grand project by pushing your PRD and wireframes to /docs.  
_Deliverable: PRD & wireframes_  

### Day 16: Backend & DB Setup Started  
Start building your backend and database.  

### Day 17: Continue Backend & n8n Logic  
Integrate n8n workflows and logic.  

### Day 18: Milestone: Backend & DB Pushed  
Push your backend to /api.  
_Deliverable: Backend & DB milestone_  

### Day 19: Frontend UI Kick-off  
Begin frontend UI development.  

### Day 20: Frontend UI In Progress  
Refine your frontend UI.  

### Day 21: Milestone: Frontend Pushed 
Push your frontend to /app.  
_Deliverable: Frontend milestone_  

### Day 22: AI Logic Integration  
Integrate AI logic.  

### Day 23: AI Logic Testing  
Test AI flows and features.  

### Day 24: Milestone: AI Flows Pushed  
Push AI code to /ai.  
_Deliverable: AI logic milestone_  

### Day 25: UI Polish & Responsiveness  
Ensure responsive design.  

### Day 26: Bug-fixing & Final Tweaks  
Fix bugs and finalize features.  

### Day 27: Public Demo Site Live    
Deploy and share your demo link.    
_Deliverable: Demo site live_    

### Day 28: QA Pass & Optimization  
Conduct QA and optimize performance.  

### Day 29: Docs & Loom Walkthrough  
Prepare docs and record a Loom.  
_Deliverable: Docs & Loom walkthrough_  

### Day 30: Final Project Demo Day   
Present your project and review code.  
_Deliverable: Final Demo Day_  


---
---

# My Experince at this Internship

## My Work

### Assignment 1
GitHub repo: [link](https://github.com/luffy-2606/Nexium_Saaif_Assign1)   
Live Site: [link](https://nexium-assignment-1.vercel.app)   

### Assignment 2
GitHub repo: [link](https://github.com/luffy-2606/Nexium_Saaif_Assign2)   
Live Site: [link](https://nexium-assignment-2.vercel.app)    

### Grand Project 
GitHub repo: [link](https://github.com/luffy-2606/Nexium_Saaif_GrandProject)    
Live Site: [link](https://nexium-project.vercel.app)      

_So these are all the assgnments + project that I did. There was as such no help given to us regarding these assignemnts/project, but rather an email was given to contact in case of any questions._

## Attendance and Deadlines
This internship was remote, so the attendance was taken through Google Classroom.    
Time-in was posted at 11:00 AM, which was due at 11:30 AM.   
Time-out was posted at 6:00 PM, which was due at 6:30 PM.   

Deadlines weren't strictly followed, all of them were delayed by one day "due to multiple requests".

## Overall Opinion
Overall, this was a great oppurtunity for students to learn. But seeing the LinkedIn posts made by the other interns, and observing their repos, most of them used AI to make their projects. And the crazy thing is they weren't even trying to hide it. Even the LinkedIn caption was written with GPT. Idk what these people are even thinking. This was an oppurtunity to learn and grow under a "professional" environment, but most used it to flex their prompting skills on the brain-dead-linkedin-cornballs.   
The main reason why the company, Nexium, offered this free internship to almost everybody was probably because they wanted to gain public attention. This can be seen from the fact that when I applied here, they had about 500 followers, but when I completed in a month they had grown to 3,500 followers. It is kind of impressive, how easy it is to gain a following/reputation by the interns flexing your internship even though you just sent them a website link with a bundle of YouTube videos attached. Great way to play the linkedin goons.
