
[![PayPayl donate button](http://img.shields.io/paypal/donate.png?color=yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=8EBB48Y35K9QG&lc=US&item_name=MiNET%20MCPE%20Server&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted "Donate once-off to this project using Paypal")

In case you don't find the information your are looking for in the README. Do try the [wiki](https://github.com/NiclasOlofsson/MiNET/wiki)

如果你想了解更多的中文信息，可以点击这里查看[中文WIKI](https://github.com/NiclasOlofsson/MiNET/wiki/MiNET-INFO%EF%BC%88In-ZH_CN%EF%BC%89)，或是进入[MiNET中文论坛](http://minetcn.com/)

MiNET
=====

[![Join the chat at https://gitter.im/NiclasOlofsson/MiNET](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/NiclasOlofsson/MiNET?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build status](https://ci.appveyor.com/api/projects/status/gb8ukrnogknic26e/branch/master)](https://ci.appveyor.com/project/NiclasOlofsson/MiNET/branch/master)

## Can I test this before I download it?
Yes, you can. At times there are dev servers running and you might be lucky enough to get in..<br>
IP: **pe.hypixel.net**    
Port: **19132**    

IP: **beta.minepocket.com**    
Port: **19132** 

## What is this?

A basic Minecraft Pocket Edition (MCPE) server written in C#. Current goal is to create a server that has enterprise performance for large Minecraft multi-user gaming providers. Current servers handle 10-100 users per instance, the aim with MiNET is to deal with thousands. Priority is also to create interfaces, and to some extend, ready-made implementations of the most basic enterprise game-management features (users, worlds, etc.). With all likelyhood, MiNET will emerge into a Microsoft Cloud ready product.

As part of the project, I also deliver an up-to-date [automatically generated MCPE Protocol Specification](/src/MiNET/MiNET/Net/MCPE%20Protocol%20Documentation.md). This is a synery of that large parts of the communication code being generated using XML and T4 templates.

## Why do this?

This is actually a pet-project - a true father-son project that I do together with my son Oliver 6 years old. He is driving the requirements for this, doing much of prioritization of the order of implementation. He is a great fan of online-MCPE gaming, but still too young to play the "real deal". He also lacks the patience and understanding of laggy under-performant servers, and the consequences of that. He is also not a big fan of the kill-style game-modes around, so a sub-project of this is for him to create new kidz-friendly game-modes that we can implement in MiNET. Oliver was the one originally responsible for creating the scope of our project.

And as he really likes to tell his mother these days "Mom, don't disturb daddy. He is working for me now!". 6 years old, but I think you get the picture. I know he does.

Lately I have also been joined by kennyvv as a full member of the team with me and Oliver. I still considering the impact of this in respect to the father-son project concept. Might be forced to adopt kennyvv at some point, we will see. I guess for now I will be the old grumpy guy and kennyvv the wise nice young guy (smartass kid, yeah).

Follow me on <a href="https://twitter.com/NiclasOlofsson" class="twitter-follow-button" data-show-count="true" data-size="large" data-dnt="true">Twitter @NiclasOlofsson</a> for news about the project, or simply track the checkins which i tend to comment heavily.

Also follow kennyvv on <a href="https://twitter.com/WuppDotNet" class="twitter-follow-button" data-show-count="true" data-size="large" data-dnt="true">Twitter @WuppDotNet</a> for even more news and updates.
 
MiNET is running CI through the fantastic service of AppVeyor. Currently the build status of master is...    
[![Build status](https://ci.appveyor.com/api/projects/status/gb8ukrnogknic26e/branch/master)](https://ci.appveyor.com/project/NiclasOlofsson/MiNET/branch/master)

## Can I do my own plugins?

Yes you can! See the [Plugin documention in the wiki](https://github.com/NiclasOlofsson/MiNET/wiki/Plugin-API-Documentation)

**Please note that the plugin system is work in progress and the example might be outdated.**

## Can I contribute?

Of course you can! We just need you to accept the following:

1. You will use the same coding style as the rest of the code.
2. You do not copy code from anyone or anywhere, unless you have their permissions.
3. We can always decide not to include your code, and we might make changes to it. So better ask before you do a pull request to the project.

Also, make sure to join our Gitter chat for easy communication.    
[![Join the chat at https://gitter.im/NiclasOlofsson/MiNET](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/NiclasOlofsson/MiNET?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Are there forums for MiNET?

Yes there's a community driven [MiNET Related Forum](http://minepocket.com/#minet-development-releated-minet-related-only.71) for sharing ideas and helping others in the community with MiNET .. stuff. Do notice that this forum does not belong to this project, so please don't contact me about it.
In case you don't get the registration email for the forum, please check your junk-mail folder or ask for help on MiNET's gitter (the admins hang out there).

## Installation

### Windows

For a windows installation you can choose to download the binary from the build server or fetch the code and compile from Visual Studio. Note that MiNET require .NET 4.6

When downloading exe & dll files from the web they will often be sandboxed - You will need to right click and unblock within the properties window to allow these to be ran without errors.

### Linux

[Linux Installation](https://github.com/NiclasOlofsson/MiNET/wiki/Running-MiNET-on-Linux)
