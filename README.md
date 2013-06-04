bluxpert
========

This is a project I did for my BSc IT Honours degree in 2010. It is an expert finding system that uses social graphs, social network analysis, and bluetooth to discover experts and influential people in your proximity.

This repository consists of:
bluXpertDesktopClient - a WPF .NET project to display a social graph of a user
UserProfileService - a WCF .NET project where REST webservices are implemented to provide User Profile functionality to users of the system
ExpertSystem - a J2ME mobile application which uses bluetooth to identify experts in the surrounding area (The User.java file contains the social network analysis algorithm for Betweenness)
