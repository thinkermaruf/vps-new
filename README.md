[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# FREE VPS with preinstalled Bug Bounty Tools!

### As per the new policies of Heroku, you are not allowed to deploy VMs and can result into account ban.


### Features:
  - Works for straight 12 hours
  - Upto 100 Mbps of Internet
  - Running on Ubuntu 18.04 Docker Image
  - Chromium and Firefox Included
  - Bug Bounty Tools Included
  - Easy to use
  - Customizable
  - Display resolution setting command:
      - xrandr -s 1440x900
      - xrandr -s 800x600
      - xrandr -s 1024x768
      - xrandr -s 1200x500
      - xrandr -s 1360x620     
      - xrandr -s 1920x1080
      
### Tools Pre-Installed:
- nuclei & nuclei templates
- dirsearch
- JSParser
- knockpy
- lazys3
- recon_profile
- sqlmap-dev
- Sublist3r
- teh_s3_bucketeers
- virtual-host-discovery
- wpscan
- webscreenshot
- Massdns
- Asnlookup
- Unfurl
- Waybackurls
- Seclists collection
- httpx
- findomain
- aquatone
- ffuf
- ParamSpider
- subfinder
- massDNS
- subDomainizer
- knockpy
- subbrute
- GittyLeaks
- Asset Finder
- Amass
- SecretX
- LinkFinder
- Subjack
- GoBuster
- XEEinjector
- XSRFProbe
- XSStrike
- Open Redirect Scanner
- NMap
- HTTProbe
- Wa00f
- gau
- BountyIt
- dalfox
- gf
- subzy
- JHaddix Wordlist
- Nahamsec Wordlist

#### Note: All tools can be found in directory root/tools
#### Special thanks to nahamsec for his bbht script which can be found here https://github.com/nahamsec/bbht

### Installation
- Create an account on Heroku
- Click on Deployment Button
- Give a name to your application and click on "Deploy App"
- Sit Back! Relax for 15-20 mins while it sets up
- Go to app_name.herokuapp.com
- Click on "Connect" in top right corner
- BOOM!! Your Free VPS is ready to go!

### Installation Video: https://drive.google.com/file/d/1Q5Ge-2IQohLNQHkoyPkHdKenlCq9z712/view?usp=sharing

#### Note 1 : GOLang is pre downloaded and extracted, the path is not set. In order to set it, you need to run the following command: export PATH=$PATH:/usr/local/go/bin
#### I have made a script "run-after-go.sh", run this once GO path gets set and all necessary tools made in GOLang will be installed.

#### Note 2 : You cannot install tools using terminal. To install any tool fork my repo: https://github.com/vlakhani28/bbht and add/delete tools you want to. Remember to change Line Number 61 in Dockerfile of the repo "vps-new" and add the link of newly forked repository.

### Limitation(s)
- If left untouched for 30-45 minutes, it gets reset. 
- Your work does not get saved, so save it on cloud like GDrive or you can use UptimeRobot(https://uptimerobot.com/) which will ping your website so the website does not get reset in 30 minutes.
- You cannot run as root user since Heroku assigns user id's randomly

### To-Do(s)
- Find a working solution for Go so that it gets pre-installed
- Add Mounting/Unmounting of GDrive 
- Add telegram notifications
- Add more tools (Twitter DM me if you want any tools to be added https://twitter.com/vlakhani28)

##### Note: The orignal code is https://github.com/RixEtte/heroku-vnc, I just modified it a bit to make this set up for Bug Bounty Hunting.
