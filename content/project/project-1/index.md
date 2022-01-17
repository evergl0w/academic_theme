---
title: "Scribo: Multi-Blog Client for Maemo/MeeGo Platform"
summary: The project is a client application for the Maemo/MeeGo platform. The latest releases (0.3x, September 2010) are written in Python and PyQt for Maemo 5.
tags:
- Mobile Linux, OSS and Maemo/MeeGo Systems
date: "2010-09-01T00:00:00Z"
author: Sergey Balandin

# Optional external URL for project (replaces project detail page).
external_link: ""

---

## Scribo: Multi-Blog Client for Maemo/MeeGo Platform

**Project Summary:**

The project is a client application for the Maemo/MeeGo platform. The latest releases (0.3x, September 2010) are written in Python and PyQt for Maemo 5.

Scribo allows representing and editing combined blog data retrieved from several blog services. It is targeted for social net users allowing them to view and edit user profiles at  their blog services and to make blog postings. The other requirements include small screen, touch-screen, and Internet connection instability. Note that they are not well satisfied in the web-browser solution, hence making Scribo more beneficial for mobile users. Furthermore, Scribo allows the user to simultaneously deal with multiple blogs from different service provides.

Scribo is oriented to mobile bloggers that regularly participate in one or more blogs. Currently it supports several blog services, e.g., **Livejournal**, **Blurty**, **InsaneJournal**, and **Dreamwidth**. The user profile aggregates information for all provided accounts and supports the following modes.

**User accounts:** Standard operations like login, read and edit account data. The user profile stores locally the data as well as information about friends and groups. The blogger can login to all preferred blogs. Now,  you can see window for adding accounts in application

Also you can delete or edit accounts.

**Postings/Comments:** Standard read/send and edit/delete operations for messages. All posts from user blogs form a list shown in corresponding page. The blogger selects a post to view the details. Currently Scribo does not have full support for comments: you can only read your comments and send comments to any post or comment.

Adding post you can se on picture below. In new version Scribo you can save drafts of your future posts and edit its later.

Two picture below show list of posts and post  text.

Also you can filter and sort your or friends posts by date, authors, content and etc.

**Multi-Blogging:** The blogger works simultaneously with several blogs. In the cross-blogging scenario, a post is duplicated to multiple blogs. To define the desired destinations blogger can select among the available set of own blogs.

On the picture you can see how you can send post on several accounts.

**Friends posts:**

Scribo allows to view not only your posts, but you can see your friends posts.

Besides Scribo allows user to view list of friends and view information about each of her/his friends

**Comments:**

Scribo allows you view comments on your own post and reply on post or comment. Besides you can delete, freeze, screen your comments  from tree of comments.

**Other scenarios:**

Our application supports some of settings: set proxy settings and application font (see on the figure below).

Besides you can send a comment about work of our application directly from application. For this you should add us in a friend from dialog in "About". Then you can read our last releases changes and comments its.

### Installation

**Custom:**

1. add repository
  - menu -> application manager
  - menu in manager -> application catalogues -> new
    + catalogue name: Maemo extras-devel
    + Web adress: <http://repository.maemo.org/extras-devel>
    + Distribution: fremantle
    + Components: free non-free
  - save
2. Run App Manager, click Download, choose item All or Network
3. Type Scribo, when item Scribo will show, click it
4. Confirm installation and go to back in common menu(exit from App Manager)

**From package:**

- Downlod scribo\'s deb on your device.
- Open Terminal on your device
- login as root
    If uoy haven\'t rootsh you must install it from application manager, and
    after that run:
        sudo gainroot
- install dependences:
    apt-get update
    apt-get install python
    apt-get install sqlite3
    apt-get install python-xml
    apt-get install python2.5-qt4
    apt-get install python2.5-qt4-network
    apt-get install python2.5-qt4-webkit
    apt-get install python2.5-qt4-gui
    apt-get install python-dbus
- install scribo package:
     dpkg -i scribo*.deb

### Online resources

- [Project Wiki (in Russian)](http://oss.fruct.org/wiki/Maemo-Blogs)
- [Open source code at Gitorious](http://gitorious.org/scribo-client)
- [Page on garage.maemo.org](http://scribo.garage.maemo.org/)
- [Bugzilla (for bug reports, either in English or in Russian)](http://oss.fruct.org/bugzilla/)
- Maillist: <maemo-scribo@cs.karelia.ru>.
- [Topic at Russian MaemoWorld forum](http://forum.maemoworld.ru/viewtopic.php?id=2585)

**Publications**

- FRUCT5 Seminar in Saint-Petersburg, April 2009. [A Cross-Blog Client for the Maemo Platform](http://oss.fruct.org/w/images/c/c8/Fruct5.pdf)
- AMICT\'2009 Workshop  in Petrozavodsk, May 2009. [A Cross-Blog Client for the Maemo Platform](http://oss.fruct.org/w/images/9/91/Amict2009.pdf)
- FRUCT6 Seminar in Helsinki, November 2010. [Diana Zaiceva, Artem Mezhenin, Aleksandr Sannikov, Kirill Germanov, Mikhail Kryshen, "A Cross-Blog Client for the Maemo Platform"](http://oss.fruct.org/w/images/0/00/Fruct_fin6.pdf)
- FRUCT7 Conference in Saint-Petersburg, April 2010. [Diana Zaiceva, Artem Mezhenin, Aleksandr Sannikov, Kirill Germanov, Dmitry Korzun, "Scribo: A Livejournal Client for the Maemo 5 Platform"](http://oss.fruct.org/w/images/0/0e/Scribo-FRUCT7slides.pdf)
- AIS/CAD 2010 in Divnomorskoye, Black Sea Coast, Russia, September 2010. Artyom D. Mezhenin, Diana V. Zaiceva, Aleksandr A. Sannikov, Kirill A. Germanov, Dmitry G. Korzun, Sergey I Balandin, Timofey V. Turenko. Scribo: Multi-Blog Client for Maemo/MeeGo Platform (accepted paper)
- FRUCT8 Seminar in Lappeenranta, November 2010. [Aleksandr Sannikov, Diana Zaiceva, Artem Mezhenin, Dmitry Korzun, "Multi-Blogging with Scribo 0.3x](http://oss.fruct.org/w/images/b/b0/Scribo03x-FRUCT8.pdf).
- FRUCT8 Seminar in Lappeenranta, November 2010. [Diana Zaiceva, Ivan Galov, Aleksandr Sannikov, Artem Mezhenin, Dmitry Korzun, "Mobile Multi-Blogging in Smart-M3: Architecture and - Scenarios](http://oss.fruct.org/w/images/7/70/FRUCT8.Mobile_Multi-Blogging_in_Smart-M3.pdf).[(article)](http://oss.fruct.org/w/images/8/87/Scribo-SS-FRUCT8paper.pdf)

**List of team members and their organizations:**

Project supervision: Dmitry Korzun

Developers:

- **Aleksandr Sannikov**  (M.Sc. student): project manager, releases, OO-paradigm, technicalities.
- **Diana Zaiceva** (M.Sc. student): problem domain, multi-blogging, coding style, GUI, Smart Spaces.
- **Artem Mezhenin** (M.Sc. student): architecture, application logic, subsystem design and data structures, testing, QMF.
- **Galov Ivan** (bachelor student): design version based on Smart M3 technology.

**Status:**

Graduate

**Project Timeline and Expected Deliverables:**

**Spring 2009.** Project plan. equirement modeling and specification. Designing a proof-of-the-concept prototype in C and GTK.

**Summer - Autumn 2009.** Refactoring the application. A workable prototype in C and GTK (with simple support of user profiles and posts).

**Winter 2009 - Spring 2010.** Moving to Python and Qt for Maemo5, testing and debugging. Adding new features: cross-bloging, friends and groups ( list of posts). Public repositoies at Gitorious.org and maemo.org. Publishing release 0.2x. Writing a research paper about Scribo.

**Summer 2010.** Finalizing release 0.2x. Moving to release 0.3x with more multi- and cross- blog elements. Elaborating an idea of implementing Scribo on top of Smart Spaces.

**Autumn 2010.** Finalizing release 0.3x with more multi- and cross- blog elements. Introducing elements of Smart Spaces.

**Winter 2011.**  Moving to Smart Space-based release 0.5x. Writing a paper about the new Scribo design and implementation.

**Final deadline:**
Wednesday, September 1, 2010 (All day)

Users:
dkorzun
zaiceva
Alexander Sannikov
galov

**Group:**
Mobile Linux, OSS and Maemo/MeeGo Systems