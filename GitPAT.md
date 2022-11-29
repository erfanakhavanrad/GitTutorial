#Subject: How to save Git PAT locally in linux based systems?

##Step 1:
Open terminal anywhere in the linux system.

##Step 2: Run one of the the Following Commands (First one is preferred)
sudo git config --global credential.credentialStore cache
git config --global credential.credentialStore cache
(It doesn't pop up any messages or so, just not having an error means it ran successfully)

##Step 3:
Clone a Project from GitHub in any directory. Type in your username and password(PAT token).

##Step 4:
After the project has been cloned, You won't be asked for username nor password in following times.
