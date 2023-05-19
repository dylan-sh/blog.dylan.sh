---
layout: post
title: 'MacroAssist: Basic Macro Automation'
---

![macroassist](https://github.com/dylan-sh/macro-assist/assets/50163127/29f44c20-d5e0-45db-ac67-84f9d8819c46)

MacroAssist was a project I worked on right before the end of my senior year of high school. It was created in Java and used JavaFX for the GUI aspect of it. This was new for me considering I came from using it's predecessor, Java Swing, for my last project (El Localizador).

The goal was to create a program that would allow highly customizable programmable macros, so that one could theoretically use it for a video game or a task. At the time, I was playing a lot of Fortnite, so I thought that I could maybe automate building by doing so. Because of this, the original name was *"Fortnite Friendo"*.

MacroAssist's GUI allowed for macros to be toggled and selected for on the fly. Macros are prewritten in a text file, using a special format that I created. You can see the sample file as "macros.txt" (MacroAssist automatically detects and parses using that filename), and it allowed for keyboard controls and mouse movements to be programmed in. For example, the line "mMove03000700	mPress	mMove05000150" would move the mouse (mMove) to a certain location on screen, press down, and move to another location. This, at the time, was something that I believe was a bit uncommon, and it could theoretically also allow for automated software and hardware testing. For ease of use, MacroAssist would also note the user's pointer location, so that it would be easier to write in.

Using JavaFX was something that was new for me, but it was considerably better and cleaner looking than my previous project. My choice of colors was a bit better this time, and this was a great project for me to end my senior year on.

MacroAssist still currently works, but requires Java 10 (obtainable through OpenJDK), as well as the now dependencies I included in the root directory of this project. I ran it recently, and the versions have been deprecated, but it still operates normally nonetheless. I guess this makes it technically cross-platform or universal since it was written entirely in Java.

Included below is a screenshot I just took of it, along with IntelliJ. Note the pointer location being printed below.

<img width="1512" alt="Screenshot 2023-05-19 at 12 50 05 AM" src="https://github.com/dylan-sh/macro-assist/assets/50163127/607f9931-4e7e-41a0-8be6-2dfba5cc64e6">
