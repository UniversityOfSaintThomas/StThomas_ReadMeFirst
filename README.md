# St. Thomas GitHub Campus - Read Me First
Welcome!

# Purpose
This GitHub organization allows individuals and teams throughout the St. Thomas community to easily store code in a central St. Thomas hub; to seamlessly share code with anyone at St. Thomas; and to make collaboration on code projects a breeze, whether within a single classroom or across multiple colleges.

# How It Works
## GitHub and Git
If you are new to Git and GitHub, learn more with GitHub's [guides](https://guides.github.com/) and [labs](https://lab.github.com/). It can also be helpful to explore training for [Git](https://git-scm.com/doc), the technology at the heart of GitHub.

## Logging in
Our GitHub Campus works by linking users' GitHub accounts to their St. Thomas accounts. When you first try to log in, go to https://github.com/orgs/UniversityOfSaintThomas/sso. You will be prompted to log into both your St. Thomas account and your GitHub account. (You will be prompted to create a GitHub account if you do not already have one.) After that, your accounts will remain permanently linked. Anyone with a valid St. Thomas account (including xtra- accounts) can join our GitHub Campus organization.

# Repositories
A *repository* (or "repo") is a project folder that contains all the information about a project, including not just files, but discussions, management options, and records of all changes ever made, who made them, and when. Most people work on repos by "cloning" (copying) the GitHub repo to their personal computer, making changes there, and then "pushing" (uploading) their work back to the GitHub repo. More on this in the [Git documentation](https://git-scm.com/doc).

If you have access to any existing St. Thomas repositories, you can see them here: https://github.com/UniversityOfSaintThomas. Repository management in GitHub Campus is largely the same as it is in regular GitHub, with a couple of small exceptions.

## Structure
The St. Thomas *organization* is the *owner* of all *repositories* stored within the org. The creator of a repository is its default *admin*. The admin decides which other teams and individuals can access the repository and exactly how much control to grant them.

## Repository Creation
You can create a repository by following [GitHub's instructions](https://help.github.com/en/enterprise/2.20/user/github/creating-cloning-and-archiving-repositories/creating-a-new-repository), or by visiting the St. Thomas GitHub Campus homepage and clicking the green "New" button in the upper-right corner. You are free to create and manage as many repos as you want.

It is important that you set the Owner to UniversityOfSaintThomas, *not* your personal account. If you do not, the repo will not be part of the St. Thomas organization and will not be able to make use of any of our GitHub Campus features. (You will still be admin on any repos you create.)

## Repository Visibility
Repositories can be *public*, *internal*, or *private*. 

### Private repos
A private repo is visible only to the teams and individuals you choose. This is the appropriate setting for most repos at St. Thomas.

### Public repos
A public repo is visible to everyone in the world, making it "open source." You **should not** use this setting unless you know what you are doing. 

You should carefully review the repo to ensure it includes no Yellow or Red data (according to the St. Thomas [data classification policy](https://www.stthomas.edu/security/policies/dataclassificationpolicy/)), attach the appropriate licenses, and obtain any required clearances. (Specific requirements vary by department and division.)

### Internal repos
An internal repo is visible to everyone within the St. Thomas community, and no one else. This does not require licensing or clearances, but, since you'll be sharing your repo with 15,000 St. Thomas faculty, staff, employees, and others, you should still be careful to follow the [data classification policy](https://www.stthomas.edu/security/policies/dataclassificationpolicy/). Since internal repos show up on *everyone's* dashboard, ITS may curate these and set them to Private at ITS's discretion. 

This ReadMe is an example of an internal repo.

## Managing Repository Access
If you are admin on a repository, you can enter the repo, click the Settings tab, then select Manage Access from the left sidebar to "invite" individuals or teams to your repo. You can assign different levels of access to different teams; the access levels are described by Git, and range from simple read-only access to full admin rights.

## Importing a Repository
Since St. Thomas's GitHub Campus is so new, you may already have repos related to your work at St. Thomas that exist outside the St. Thomas GitHub Campus organization. You can transfer ownership of a repository from your personal account to the St. Thomas organization by following [these instructions](https://help.github.com/en/github/administering-a-repository/transferring-a-repository).

When you transfer a repo to St. Thomas ownership, your admin rights are downgraded to write access. This is an annoying quirk. The GitHub Campus Administrator (currently me, [James Heaney](mailto:jjheaney@stthomas.edu)) will receive a notification whenever this happens and will restore your admin rights in a timely manner. However, some of our users prefer to avoid the issue by creating a new repo within the St. Thomas org (so they have admin rights), then pushing their old personal repo to the new St. Thomas repo, then finally deleting the old repo.

# Teams
The St. Thomas organization contains a number of *teams*. Teams offer a way for specific individuals to discuss and collaborate among themselves, and they are a marvelously convenient way to manage permissions for repositories. 

For example, if you have 12 repos you want to share with another unit at St. Thomas, and that unit has 15 members, you can either add each member to each repo individually (and go through every repo again when Linda gets promoted out and they hire a new member)... or you can assign access to that unit's GitHub team, and let them manage their team's changes. You'll almost always want to manage access to repos using teams instead of individual accounts.

You can view the existing teams here: https://github.com/orgs/UniversityOfSaintThomas/teams. At this writing, ITS has created only a few teams focused on ITS, but we plan to add more soon.

### Team Creation Etiquette
Any user of the St. Thomas GitHub Campus Organization is free to create and manage teams -- as many as you want. You can do so by visiting the [Teams page](https://github.com/orgs/UniversityOfSaintThomas/teams) and clicking the green "New team" button in the top right corner. 

We request that any teams you create be set to Secret (not Visible). The list of Visible teams is curated by ITS.

ITS is available to help you set up your teams -- especially if you would like to create a Visible team. Email techdesk@stthomas.edu and note in the email that the ticket should be sent to the GitHub Campus Administrator, James Heaney.

A new team must be configured to be *synchronized* or *unsynchronized*. Here is what that means:

### Synchronized Teams
A synchronized team is connected to a specific St. Thomas Active Directory group (like "Group: Chess Club" or "Biology Faculty and Staff DG"). GitHub Campus "syncs" with St. Thomas Active Directory once every hour and automatically updates the members of your synchronized GitHub Campus team. Anyone who has joined the A.D. group is added to the team; anyone who is no longer in the A.D. group is removed. This means you don't have to deal with constantly managing team membership when new employees or students are hired and others depart; Active Directory handles all that behind-the-scenes.

If you are a team's admin (or are creating a team), you can connect it to a St. Thomas Active Directory group using the Identity Provider Groups option in the team's Settings >> General tab (or on the team creation screen). The Identity Provider Groups lookup menu searches A.D. for groups that match what you've typed in.

*Tip: The lookup menu is not a freeform search, but a quite rigid lookup; if the group you are looking for is called "Group: UST Chemistry Department Stockroom," you must type in "Group: UST Chem" to find it. Typing in just "Chemistry" will not find it.*

#### Active Directory Groups
You can find a list of the most commonly-used A.D. groups in [Outlook People Online](https://outlook.office.com/people/) under Directory >> All Distribution Groups (on the left sidebar). 

Some of these groups are managed automatically by ITS using Banner data. Those groups start with the prefixes "Auto:", "Staff:" and "Acad:". You can find more information about them on our [Automated Email Distribution Groups page](https://one.stthomas.edu/sites/its/SitePage/62788/auto-email-distribution-groups), and you can easily search for them using [Outlook people search](https://outlook.office.com/people/). For example, if you want all full-time faculty in the School of Engineering to be members of a team, you would connect the team to "Auto: Faculty - Full-Time - School of Engineering."

Other groups, especially the ones with the "Group:" prefix, are managed manually by Outlook group owners. 

### Unsynchronized Teams
An unsynchronized team is created in GitHub but not connected to any St. Thomas group. The team's admin must manually manage its member list within GitHub campus. This is done through the team's Members tab. It is simpler to set up initially, but more arduous to manage. Unsynchronized teams may also have child teams. (Synchronized teams may not.)


