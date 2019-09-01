---
published: true
---
## The Transition from Mac to Windows

The decision as to which operating system is chosen by (or for) oneself continues to get murkier.  Corporates that were once steadfast Windows-only are expanding their horizons to Mac and even Linux along with varying levels of gaming.  That aside, my dear ever-aging Macbook Late 2010 has been augmented with a modest 100GB SSD, more Ram (8GB but not at it's limit) but it has been limping on one USB port, is on it's third charger and becoming more physically cumbersome for hauling around.  Possibly the final driver for an upgrade is that this machine doesn't officially receive the latest Mac OS version 10.14 "Mojave" and FileVault does burden the loyal Core 2 Duo processor.

The thought of upgrading was intimidating: did I re-invest in a new or used Macbook?  Did I make the transition back to a reasonable Windows Machine?  Was my first step to simply run Ubuntu?

A good-priced Microsoft Surface Pro 3 became available and while they weren't well-received at work (the majority of our team believed our build simply hadn't had the attention that it deserved in order to iron out the issues), I decided to take the cost-effective dive-in.

I was immediately reminded I had previously renounced the 'floppy' detachable keyboard cover after tolerating it briefly on an HP Elite X2 while network engineering in akward spots.  I still persisted with the Surface Pro and overlooked this inconvenience because of the price.

The next internal quandry, as I mentioned before, was either come to terms with Microsoft Windows or throw it out in favour of Linux.  A few years of adapting to Mac OS, and many years on a Linux desktop prior, has spoiled me for command line capabilities.  The good news is, Microsoft's metamorphasis into a seemingly co-operative corporation has delivered Windows Subsystem for Linux (WSL) to run some Ubuntu (with caveats), Docker for Windows, Visual Studio Code and surely hell got a bit chillier the day the company released SQL Server for Linux.  For all intents and purposes, Microsoft are in the good-books for the time being.

So far the only thing that I have bumped into was the fact that I am faced with the unavoidable re-purchase Affinity Designer from Serif for Windows.  I'm deferring that for now.

Here are some of the equivalents I matched up:


| Mac OS                                          | Windows                                            |
| Installed via [Homebrew](https://brew.sh/) when possible | Installed via [Chocolatey](https://chocolatey.org/) when possible |
| --- | --- |
| iTerm2                                          | ConEmu                                             |
| Bash Native                                     | Bash via WSL/Ubuntu 18.04                          |
| mtr, dig, whois                                 | winmtr-redux, bind-toolsonly, whois                |
| XQuartz                                         | VcXsrv                                             |

Currently the experience is far from optimised for my command-line dalliances (a bit more learning to be done on ConEmu) over the variety of shells - Powershell, Bash, CMD and admin variations - but I'm getting there.  The added benefits of a more-native docker, Hyper-V and the occasional game that I couldn't play on my old Macbook makes up for it anyway.

Only time will tell if I don't simply install Ubuntu instead!
