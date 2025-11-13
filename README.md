# MILLAN'S DEV WORKFLOW

1. **Create Repo:** use consistent naming conventions:  
-- lab-9.2-character-counter <br>
-- sba9-react-dashboard-app <br>

2.  **Initialize Project**: Make sure you're inside your module folder and `npm create vite@latest` - use same name as repo, choose React and Typescript <br>

3. **Install Dependencies, Configure Workspace, and Run Project**: <br>
-- `cd` into project folder <br>
-- `npm i` <br>
-- file > open folder > choose project folder <br>
-- open 3 terminal windows, name them 'server', 'git', and 'installs' <br>
-- inside the 'server' terminal, `npm run dev` to start server <br>

4. **Install Tailwind**: 
-- in your 'installs' terminal - `npm install tailwindcss @tailwindcss/vite`<br>
-- <b>vite.config.ts</b> - `import tailwindcss from '@tailwindcss/vite'`<br>
-- add tailwind to plugins array: `[    tailwindcss(), react()  ],`<br>
-- <b>index.css</b> - add `@import "tailwindcss"` at the top<br>
-- this will be your this your main styles file <br>

5. **Clean Up**: delete boilerplate folder, files, code, and related imports: <br>
-- delete public + assets folders, App.css <br>
-- <b>index.html</b>: delete svg (no need to add css file here when you're using react), update title <br>
-- Appt.tsx: delete all imports and replace all JSX with an header with app name <br>

6. **Create File Structure**: 
-- add your project folders and files as per project instructions <br>
-- replace contents of README.md with project info from canvas <br>
-- create a to-do.md, paste project tasks with [ ] next to them (use AI for this, faster) <br>
-- create notes.txt file for your own use, add it to .gitignore <br>

7. **Make First Commit**: initiate local repo and make first commit:
-- `git init` <br>
-- `git add .` <br>
-- `git commit -m "first commit"` <br>
-- `git branch -M main` <br>
-- `git remote add origin [url]` <br>
-- `git push -u origin main` <br>

8. **Manage Time Wisely, Make a Plan**: strategize a plan for the project before you start coding! <br>
-- first priority is achieving MVP, so start with most important tasks first <br>
-- logic and functionality first. leave styling till the end (you don't decorate a house before building it!) <br>

9. **Start Coding!** Yeeeeee! <br>
-- push changes to your repo frequently using clear commit messages with consistent language, this way you can always go back to your last working version when you break your app. <br>
-- use console.logs/ sanity checks frequently. if something doesn't work - first check if its wired up correctly. <br>
-- google error messages, don't just go changing stuff until you know what the issue is <br>
