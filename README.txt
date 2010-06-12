This file is a very simple JavaScript/HTML page that provides the ability to select and dynamically update True20 Villain Roles, as defined by the gang on the True20 Forums.

You need JQuery to run this page -- just download it from JQuery.org and stick the jquery.js file in the same directory as the villainpicker.html.

villainpicker.html requires you to supply it with data in order for it to work. The existing page has the data for the "Artillery" already added but if you want to use this for all roles you'll need to supply the data dynamically. The files ending in ".data" include the required data for each role. You'll also want to set the "name" variable dynamically, I bet.

The DINO-PIRATES OF NINJA ISLAND implementation of this also provides static links to each level of each role but that was built out of the Django back-end on the DPoNI site, so we've left that to the reader's imagination. You can just peek at our code to see how we did it.

Much thanks to The Shadow, Baduin, iwatt and ValhallaGH for actually doing most of the creative work here.

This file and the file "villainpicker.html" are public domain. The data files are entirely Open Game Content and are released under the Open Gaming License 1.0, reproduced below:

OPEN GAME LICENSE Version 1.0a

The following text is the property of Wizards of the Coast, Inc. and is Copyright 2000 Wizards of the Coast, Inc ("Wizards"). All Rights Reserved.

1. Definitions: (a)"Contributors" means the copyright and/or trademark owners who have contributed Open Game Content; (b)"Derivative Material" means copyrighted material including derivative works and translations (including into other computer languages), potation, modification, correction, addition, extension, upgrade, improvement, compilation, abridgment or other form in which an existing work may be recast, transformed or adapted; (c) "Distribute" means to reproduce, license, rent, lease, sell, broadcast, publicly display, transmit or otherwise distribute; (d)"Open Game Content" means the game mechanic and includes the methods, procedures, processes and routines to the extent such content does not embody the Product Identity and is an enhancement over the prior art and any additional content clearly identified as Open Game Content by the Contributor, and means any work covered by this License, including translations and derivative works under copyright law, but specifically excludes Product Identity. (e) "Product Identity" means product and product line names, logos and identifying marks including trade dress; artifacts; creatures characters; stories, storylines, plots, thematic elements, dialogue, incidents, language, artwork, symbols, designs, depictions, likenesses, formats, poses, concepts, themes and graphic, photographic and other visual or audio representations; names and descriptions of characters, spells, enchantments, personalities, teams, personas, likenesses and special abilities; places, locations, environments, creatures, equipment, magical or supernatural abilities or effects, logos, symbols, or graphic designs; and any other trademark or registered trademark clearly identified as Product identity by the owner of the Product Identity, and which specifically excludes the Open Game Content; (f) "Trademark" means the logos, names, mark, sign, motto, designs that are used by a Contributor to identify itself or its products or the associated products contributed to the Open Game License by the Contributor (g) "Use", "Used" or "Using" means to use, Distribute, copy, edit, format, modify, translate and otherwise create Derivative Material of Open Game Content. (h) "You" or "Your" means the licensee in terms of this agreement.

2. The License: This License applies to any Open Game Content that contains a notice indicating that the Open Game Content may only be Used under and in terms of this License. You must affix such a notice to any Open Game Content that you Use. No terms may be added to or subtracted from this License except as described by the License itself. No other terms or conditions may be applied to any Open Game Content distributed using this License.

3.Offer and Acceptance: By Using the Open Game Content You indicate Your acceptance of the terms of this License.

4. Grant and Consideration: In consideration for agreeing to use this License, the Contributors grant You a perpetual, worldwide, royalty-free, non-exclusive license with the exact terms of this License to Use, the Open Game Content.

5.Representation of Authority to Contribute: If You are contributing original material as Open Game Content, You represent that Your Contributions are Your original creation and/or You have sufficient rights to grant the rights conveyed by this License.

6.Notice of License Copyright: You must update the COPYRIGHT NOTICE portion of this License to include the exact text of the COPYRIGHT NOTICE of any Open Game Content You are copying, modifying or distributing, and You must add the title, the copyright date, and the copyright holder's name to the COPYRIGHT NOTICE of any original Open Game Content you Distribute.

7. Use of Product Identity: You agree not to Use any Product Identity, including as an indication as to compatibility, except as expressly licensed in another, independent Agreement with the owner of each element of that Product Identity. You agree not to indicate compatibility or co-adaptability with any Trademark or Registered Trademark in conjunction with a work containing Open Game Content except as expressly licensed in another, independent Agreement with the owner of such Trademark or Registered Trademark. The use of any Product Identity in Open Game Content does not constitute a challenge to the ownership of that Product Identity. The owner of any Product Identity used in Open Game Content shall retain all rights, title and interest in and to that Product Identity.

8. Identification: If you distribute Open Game Content You must clearly indicate which portions of the work that you are distributing are Open Game Content.

9. Updating the License: Wizards or its designated Agents may publish updated versions of this License. You may use any authorized version of this License to copy, modify and distribute any Open Game Content originally distributed under any version of this License.

10 Copy of this License: You MUST include a copy of this License with every copy of the Open Game Content You Distribute.

11. Use of Contributor Credits: You may not market or advertise the Open Game Content using the name of any Contributor unless You have written permission from the Contributor to do so.

12 Inability to Comply: If it is impossible for You to comply with any of the terms of this License with respect to some or all of the Open Game Content due to statute, judicial order, or governmental regulation then You may not Use any Open Game Material so affected.

13 Termination: This License will terminate automatically if You fail to comply with all terms herein and fail to cure such breach within 30 days of becoming aware of the breach. All sublicenses shall survive the termination of this License.

14 Reformation: If any provision of this License is held to be unenforceable, such provision shall be reformed only to the extent necessary to make it enforceable.

15 COPYRIGHT NOTICE Open Game License v 1.0 Copyright 2000, Wizards of the Coast, Inc.
System Reference Document, Copyright 2000, Wizards of the Coast, Inc., Authors Jonathan Tweet, Monte Cook, Skip Williams, based on original material by E. Gary Gygax and Dave Arneson. 
Modern System Reference Document Copyright 2002-2004, Wizards of the Coast, Inc.; Authors Bill Slavicsek, Jeﬀ Grubb, Rich Redman, Charles Ryan, Eric Cagle, David Noonan, Stan!, Christopher Perkins, Rodney Thompson, and JD Wiker,  based on material by Jonathan Tweet, Monte Cook, Skip Williams, Richard Baker, Peter Adkison, Bruce R. Cordell, John Tynes, Andy Collins, and JD Wiker. 
Advanced Player’s Guide, Copyright 2004, White Wolf Publishing, Inc. 
Blue Rose, Copyright 2005, Green Ronin Publishing; Authors Jeremy Crawford, Dawn Elliot, Steve Kenson, Alejandro Melchoir, and John Snead. 
Monte Cook Presents: Iron Heroes, Copyright 2005, Monte J. Cook. All rights reserved. 
Mutants & Masterminds, Copyright 2002, Green Ronin Publishing; Author Steve Kenson. 
The Psychic’s Handbook, Copyright 2004, Green Ronin Publishing; Author Steve Kenson. 
Unearthed Arcana, Copyright 2003, Wizards of the Coast, Inc.; Andy Collins, Jesse Decker, David Noonan, Rich Redman. 
True20 Adventure Roleplaying, Copyright 2005, Green Ronin Publishing; Author Steve Kenson. 
Caliphate Nights, Copyright 2006, Paradigm Concepts; Author Aaron Infante-Levy 
Lux Aeternum, Copyright 2006, BlackWyrm Games; Author Ryan Wolfe, with Dave Mattingly, Aaron Sullivan, and Derrick Thomas. 
Mecha vs. Kaiju, Copyright 2006, Big Finger Games; Author Johnathan Wright 
Borrowed Time, Copyright 2006, Golden Elm Media; Authors Bruce Baugh and David Bolack
True20 Villain Roles written by ValhallaGH

