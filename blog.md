% Sean's Christmas Hack Blog
% Sean Davis
% December 2016

Introduction
=============

I've got a few days off over Christmas, so before the celebrations start I am going to quickly build something. The last few months I have spent a lot of time consulting and not much time building. Time to hack something cool together to see if I've still got it.

User story
----------

As a bored dude 
I want to build and document something cool
So that I can pass the time whilst practising my dev skills

Day 0
======

Planning - 23:25
-----------------
I'll start off bright and early tomorrow by rebuilding my dev environment. For now I'll just create this git repo and start off this blog. I'll be using pandoc to convert the markdown before publishing it somewhere.

Day 1 
======

Development Environment Setup - 12:09
--------------------------------------

After a long lie-in, I have rebuilt my development machine. I am running an Acer C720 Chromebook with SeaBIOS. In order to maximise he small amount of memory and disk space I have, I have installed the absolute minimum I can get away with. After setting up Ubuntu 16.04 Server Edition, I installed the following:

```
sudo apt-get install -y plasma-desktop vim git tmux xinit xfce4-terminal firefox
curl -sSl https://get.docker.com | sh
```

Next up: Planning
