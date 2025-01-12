# JDownloader 2 Offline Captcha solver
JDownloader already solves a lot of captchas on its own, but for some hosts you have to input the result by hand. This tool reduces the list of unsupported hosts.

Using [YOLO DARKNET](https://pjreddie.com/darknet/yolo/) as neuronal Network to solve captchas!

## Installation Windows
1. Download the latest standalone zip: [win](https://github.com/cracker0dks/CaptchaSolver/releases/download/v2.0.2/CaptchaSolver-v2.0.2_standalone_win.zip)
2. Extract the "JDownloader 2.0" content in your current JD2 folder
3. restart JD2 and start downloading

## Installation Linux & Mac
1. Clone this repository
2. Download and compile [AlexeyAB's fork of darknet](https://github.com/AlexeyAB/darknet)
3. Copy the resulting darknet executable to `/JDownloader 2.0/tools/offlineCaptchaSolver/darknet64/darknet`
4. Install NodeJS and make sure it's available in your PATH
5. Copy the "JDownloader 2.0" content into your current JD2 folder (probably `~/.jd`)
6. Restart JD2 and start downloading

## Deactivate The Captcha Solver for Hosts
This come in handy if the host changed the captcha type and you have to deactivate some hosts...

1. Go to ...\JDownloader v2.0\jd\captcha\methods\ 
2. Move the folders of the hosts you want to deactivate "keep2share_linux", "keep2share_win" to another save location
3. Restart JDownloader 2

To activate them again, just copy them back in and restart JD2

## Supported Types of Captchas
### 6 Digits Captcha (NEW)
![ks](/docs/i1.jpg)

Known Hosts with this captcha:
* keep2share.cc / k2s.cc;
* fileboom.me
* tezfiles.com
* depositfiles.com

Docu on how this Captcha is solved: [HERE](docs/howToSolveNew6DigitCaptchasWalkthrough.md)

## Old captchas (not used anymore)
Download v1.x to get the code for solving this captchas!

### 6 Digits Captcha
![ks](/docs/ksinput.gif)

Docu on how this Captcha is solvede: [HERE](docs/howToSolve6DigitCaptchasWalkthrough.md)

### 4 Digits Captcha
![ks](/docs/xFQIX.png)

Known Hosts with this captcha:
* przeklej.org

DDocu on how this Captcha is solved: [HERE](docs/howToSolve4DigitCaptchasWalkthrough.md)

---------------------

Thanks to Corubba for the linux part on v2.x!

