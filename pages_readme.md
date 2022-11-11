# GitHub Pages (Web Hosting) @ St. Thomas - Read Me First

# What is GitHub Pages?
GitHub Pages changes your standard GitHub repositories into hosted websites, which you can customize however you want. This is ideal if you have built a website for a specific course, conference, or project; if you need personal control of your website at your fingertips; if you have some knowledge of how to write HTML webpage code; and if you don't want (or can't have) university branding on your web content. Content that previously lived on PersonalWeb or CourseWeb are ideally suited for migration to St. Thomas's GitHub Pages.

# How to Do It
1. Create your HTML/CSS/JS website on your local computer (or, if it already exists, get a copy of it from CourseWeb). 
  - If you don't have any idea how to make a webpage, GitHub Pages *may* not be the right solution for you, but talk to ITS.
  ![A small website on my computer](/screenshots/pages_1_smallwebsite.png)
2. [Create a repository](https://github.com/organizations/UniversityOfSaintThomas/repositories/new) within the University of St. Thomas organization.
  - The name you choose for this repository will be part of the your website's URL when you are done, so pick a good one!
  - Set the repository visibility to Public. (If you set the visibility to Private or Internal, [as your normally would](https://github.com/UniversityOfSaintThomas/StThomas_ReadMeFirst/), your website will have a randomly generated URL.
  ![Repo creation](/screenshots/pages_2_newrepository.png)
3. Upload your website to the repository you just created. This is easiest through the Add Files dialogue, which you can access by clicking on "Uploading an Existing File" just after your repository is created (or on Add File --> Upload Files later on):
  - You do not need a license, and, in general, should avoid adding licenses to St. Thomas repositories without talking to the St. Thomas Office of General Counsel.
  ![Upload via Add Files](/screenshots/pages_3_clickupload.png)
4. Drag and drop your website into the repostory and click "Commit."
  ![Commit new files](/screenshots/pages_4_addfiles.png)
5. Now that your website is in git, we'll turn on GitHub Pages. Go to Settings, then to Pages.
  ![Where is settings](/screenshots/pages_5_settings.png)
  ![Where is pages](/screenshots/pages_6_pages.png)
6. Enable Pages by setting the source branch to main. Then press Save.
  - You can use another branch if you want, but, 99% of the time, main makes the most sense.
  ![Setting a source branch](/screenshots/pages_7_branch.png)
7. Wait 3-5 minutes. GitHub will now deploy your website to a GitHub Pages URL, and that takes a short time. After 3-5 minutes, refresh the Pages Settings. You should see a live deployment notice. Your repo will be deployed at universityofsaintthomas.github.io/\[your_repo_name\]
  ![Deployment notice](/screenshots/pages_8_deployment.png)
  - If your URL is not under universityofsaintthomas.github.io, it is probably because either:
    - (a) you did not create your repo as part of the University of St. Thomas organization. [Import the repo into the UST organization](https://github.com/UniversityOfSaintThomas/StThomas_ReadMeFirst) to fix this.
    - or (b) you made your repo visibility Private or Internal. Set your repo's visibility to Public to fix this. (This is done in Settings >> General >> Danger Zone.)
8. You can now visit your website by clicking the Visit Site button. Please do so! Make sure it all works correctly!
9. Since this is now a git repository, you can edit your website at any time by editing the web pages directly in GitHub, or by cloning the repository to any computer and revising it there.
10. Since these repositories are public, please take care not to put any confidential data in them! Thank you!

# No Thank Yous
- Please do not use St Thomas's GitHub Pages to host your personal business website.
- ...or anything illegal.
- ...or anything that violates the Catholic mission of the school, including racism, pornography, and other obviously terrible ideas.
- Although designed to empower faculty, staff, and students to create their own websites with minimal oversight, St. Thomas does still own this webspace, and will pull down any problematic content.
  
# Questions?
ITS is available to provide any assistance you may need with the St. Thomas GitHub, including GitHub Pages. Email techdesk@stthomas.edu to open a support ticket (cc jjheaney@stthomas.edu).
