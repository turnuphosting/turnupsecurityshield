# turnupsecurityshield
TurnUpSecurityShield Server Tools provides Strong Security Protection for Linux Servers.

# Before Begining, Read the Instructions Below Carefully.
The script will automatically download, install, and optimize the rules for CSF, Rootkit Hunter, and other essential Server Security tools on your server saving you precious time and effort.

Remember to regularly update and configure these tools to ensure the ongoing security of your server or system.

This also provides Server Side Bruteforce Protection by Implementing Recaptcha v2 on the server for most login pages of CMS like WordPress without any hassle.

This is licensed under the GNU General Public License v3.0 and a copy of the license is included in this repo.

**Please Note:**
The command should only be run with caution in a terminal for eg. an SSH terminal. 

TurnUpSecurityShield Server Protection Tools **Generic Version** should only be **installed on fresh or new RHEL-Based Servers** (CentOs, AlmaLinux, etc) **with No Already Installed Panels** (eg. cPanel/WHM, DirectAdmin, CyberPanel, etc).

Run the command below that is based on your current server settings as described in the version listed above.

# Run the command below to Install TurnUpSecurityShield Server Protection Tools Generic Version

**sudo curl -o turnupsecshield_tools.sh -L https://github.com/turnuphosting/turnupsecurityshield/releases/download/downloads/generic_turnupsecshield_tools.sh && sudo bash generic_turnupsecshield_tools.sh**
