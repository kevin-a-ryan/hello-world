# hello-world
to practice github
*Github terminology in ALL CAPS

REPOSITORY is a project organizer for folders and data.
BRANCHING is for version control of the files in the project repository
    MASTER BRANCH = default definitive branch (it should always be deployable)
    NEW/FEATURE BRANCH = snapshot of master branch for working on changes (new branch names should be descriptive)
Edits to a feature branch are saved in the feature branch using a COMMIT action
    COMMITS can be named and descriptions of the saved changes can be added
PULL REQUESTS initiate the process of merging a FEATURE BRANCH with the MASTER BRANCH
	Differences between the code can be viewed using the COMPARE CHANGES feature
	Each PULL REQUEST can be named and descriptions can be added
	Submitting a PULL REQUEST does not automatically merge the FEATURE BRANCH with the MASTER BRANCH
	Submitting a PULL REQUEST initiates a CONVERSATION about the changes that team members can review and comment on
	Team members can review meta data regarding the PULL REQUEST
A MERGE occurs when a team member accepts the changes in the PULL REQUEST and chooses to MERGE to the MASTER BRANCH
	A MERGE must be CONFIRMED
	The FEATURE BRANCH can be deleted after the merge
	Team members can still comment on the PULL REQUEST CONVERSATION after it has been MERGED to MASTER BRANCH
Download Github Desktop application
	CLONE your online Github.com repository to the desktop application by establishing a local folder
	You can continue to use Github features in desktop such as creating new REPOSITORIES/BRANCHES
	Click FETCH ORIGIN in Github Desktop in order to sync the local BRANCH to a Github.com REMOTE BRANCH/REPOSITORY
	Github calls the github.com DEFAULT REMOTE REPOSITORY = ORIGIN
	PULL ORIGIN means to sync COMMITS (changes) made in the cloud with the local files
	Make and save changes to the local files using local apps (notepad/RStudio, etc.)
	Github Desktop will compare changes with the ORIGIN file in the cloud. COMMIT the changes in Github Desktop.
	You can also MERGE the FEATURE BRANCH into the MASTER BRANCH in Github Desktop by:
		Change to the BRANCH you want to MERGE into, then click 'Choose a branch to merge into branch'
	Use PUSH ORIGIN feature to MERGE the local changes to the ORIGIN REPOSITORY on Github.com
	If you make a new local BRANCH while in Github Desktop, you can PUBLISH the new BRANCH
		PUBLISH BRANCH = PUSH a new local BRANCH to a REMOTE Github.com REPOSITORY (ORIGIN)

FORKS
	FORK is a copy of a REPOSITORY
	To make suggestions on someone's project
		FORK the REPOSITORY, edit the code, SUBMIT PULL REQUEST to project OWNER
		The OWNER can then review the changes
	Can also FORK a REPOSITORY to build something new off of it
