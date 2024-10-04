Enter the following in CMD; Run as Administrator:

color a & curl parrot.live

Color a

dir/s

help color

telnet towel.blinkenlights.nl

Python Color Change Code:

function prompt
{
    Write-Host "PS $(get-location)>"  -nonewline -foregroundcolor Magenta
    return ' '
}

To open or create a PowerShell profile, run this:

if(Test-Path $profile){notepad $profile}else{New-Item -path $profile -type file -force}

How to Fix Slow Copy Speed and Optimize Drives on Windows:

Run CMD as Admin: netsh int tcp set global autotuninglevel=disable

Then Open Services, Click on Optimize Drives Services, Change the Startup Type to Automatic and Select Start.

Windows Command Prompts. List of All Apps on PC:

shell:appsfolder

Windows PowerShell Command For Multi Tool:

iwr -useb https://christitus.com/win |iex

How to Update All Applications on Windows Through CMD as Admin:

First Enter: winget - upgrade

Then Enter: winget - upgrade --all

Full Command: winget update --all --include-unknown --accept-source-agreements --accept-package-agreements --silent
