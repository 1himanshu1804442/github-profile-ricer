---
name: github-profile-ricer
description: Automatically revamps a user's GitHub profile README to look premium, dynamic, and spectacular with typing SVGs, animated metrics, and beautiful badges.
---

# GitHub Profile Ricer

When the user asks you to revamp, upgrade, or "rice" their GitHub profile README, follow these steps exactly:

1. **Locate the Profile Repository**
   Find or ask the user for their profile repository (the repository with the same name as their GitHub username). Ensure you read the existing `README.md` to gather their current information.

2. **Extract User Data**
   Extract their Name, Job Titles/Roles, Tech Stack, Social Links (LinkedIn, LeetCode, Email, etc.), and their Top 3-4 Featured Projects.

3. **Design the Premium README**
   Overwrite their existing `README.md` using the exact structure below. Be sure to replace placeholders like `[GITHUB_USERNAME]` with actual data, and adapt the `skillicons.dev` URL to include their tech stack.

   ```html
   <!-- Header Section -->
   <h1 align="center">
     <!-- NOTE: Do NOT use unencoded emojis in the lines= parameter, it will break the SVG rendering! -->
     <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Hi,+I'm+[NAME];[ROLE+1];[ROLE+2];[ROLE+3]" alt="Typing SVG" />
   </h1>

   <p align="center">
     <img src="https://komarev.com/ghpvc/?username=[GITHUB_USERNAME]&style=flat-square&color=007ec6&label=Profile+Views" alt="Profile Views" />
   </p>

   <p align="center">
     <a href="https://linkedin.com/in/[LINKEDIN]" target="_blank">
       <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
     </a>
     <!-- Add LeetCode and Email badges here, always using target="_blank" -->
   </p>

   <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header" width="100%" />

   ### 🚀 About Me

   [Write a compelling, professional bulleted introduction here based on their background]

   <br/>

   ### 🛠️ Tech Stack & Tools

   <p align="center">
     <a href="https://skillicons.dev">
       <img src="https://skillicons.dev/icons?i=[TECH_COMMA_SEPARATED]&perline=7" alt="Tech Stack" />
     </a>
   </p>

   <br/>

   ### 🌟 Featured Projects

   <table width="100%">
     <tr>
       <td width="33%" valign="top">
         <h3 align="center">🛡️ [Project 1 Name]</h3>
         <p>[Short Description]</p>
         <p align="center"><a href="[PROJECT_LINK]"><strong>Explore Project »</strong></a></p>
       </td>
       <!-- Add more <td> columns for other projects -->
     </tr>
   </table>

   <br/>

   ### 📈 GitHub Analytics

   <p align="center">
     <img src="https://github-readme-stats.vercel.app/api?username=[GITHUB_USERNAME]&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&bg_color=0D1117" alt="GitHub Stats" width="49%" />
     <img src="https://github-readme-streak-stats.herokuapp.com/?user=[GITHUB_USERNAME]&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" width="49%" />
   </p>

   <p align="center">
     <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[GITHUB_USERNAME]&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" width="49%" />
     <!-- Optional: Add LeetCard if they have a LeetCode account -->
   </p>

   <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" width="100%" />
   ```

4. **Commit and Notify**
   - Automatically commit and push the newly styled README to the user's repository.
   - Summarize the premium features you added (Typing SVGs, Skillicons, Capsule Render, Dark Mode Analytics).
