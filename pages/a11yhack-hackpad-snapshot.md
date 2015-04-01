---
published: true
permalink: /a11yhack/hackpad-snapshot/
layout: default
title: Hackpad Snapshot - Accessibility Hackaton
page_title: Hackpad Snapshot
description: 'This is a snapshot of the notes on from the hackpad.'
---

A lot of collaboration during the hackathon happened on through via the [Hackpad](https://hackpad.com/Accessibility-Hackathon-a11yhack-FSW5lFX53LP). A hackpad is a space where individuals can collaborate around connect in an interactive way. The content of this page is a snapshot of the hackpad information. The information was captured on April 1, 2015 @ 6:30 p.m., and may not reflect changes after that point in time. The formatting of this snapshot is intended to reflect the meaning of the original content, but may have been edited for clarity.

Everything beyond this sentence is from the hackpad.

-----

## Accessibility Hackathon - #a11yhack

*March 31, 2015*

Hosted by [The White House Office of Science and Technology Policy](https://www.whitehouse.gov/administration/eop/ostp), [18F](https://18f.gsa.gov/), [the National Institute on Disability, Independent Living, and Rehabilitation Research](http://www2.ed.gov/about/offices/list/osers/nidrr/index.html), and [DC Legal Hackers](http://dclegalhackers.org/).

[a11yhack website](http://18f.github.io/hackathons/a11yhack/)

### Problem Statements

#### Web Design

* Problem: the process of evaluating whether or not federal IT acquisition contracts and proposals are 508-compliant is currently very manual. Is there any way to automate the evaluation of contract/proposal language to either determine if a contract is 508-compliant or to limit the number of contracts that need to be manually evaluated?
* What kinds of templates can we devise that content creators/developers can use.
* How best to structure tree-like data on the web? How can that sort of structured data be most efficiently/easily browsed with a screen reader?
* CAPTCHAs need to be more accessible for the deaf/blind community.  Audio CAPTCHAs do not work for that community nor do they work well due to problems with individual’s PC/laptop speakers/audio as well as problems with users in poor bandwidth areas. Additionally, screen readers talk over the audio. (The latest audio captchas from reCaptcha are incomprehensible even to those with perfect hearing. Really terrible stuff.)

#### Maps

* [Example](http://beta.foreignassistance.gov/) from [this tweet](from https://twitter.com/ForeignAsst_gov/status/582917347331166208) by ForeignAsst_gov.
* Look at user modalities
    * Blind - use fallback content within Canvas to provide headings for regions and countries.
    * Low vision - add keyboard access, make sure site can be zoomed and style be usable.  Check high contrast.  Zoom features conflict - pinch zoom zooms map but not other content -- other zoom keystrokes need to be used for whole page zoom up to 200%
        * When you zoom in text may appear over top of other text.
        * Disclosure component to hide and show legend so it isn’t in way when you zoom in.
    * Colorblind -  use patterns such as hatching, dots, lines, etc. in addition to color.  Use colorblind safe colors
    * Motor impairments - keyboard access to zoom in and out and move to all countries and show popups on focus in addition to hover
        * Larger clickable areas that automatically focus on Points of Interest
        * Make sure popups don’t interfere with access
        * Keyboard access to scroll map horizontally and vertically
        * Mode that doesn’t pop-up content as you mouse around.

#### Workflows & Process

* How can we help other federal agencies include 508/accessibility experts from the onset, instead of after a project has been fully developed. It is often an after thought (advocacy/communication plans?)
* Design considerations for 3D printable augmentations to mobile devices for users with newly limited dexterity (ie, stroke, accident) -- designing not just for usability but for rehabilitation and recovery.
* Developing modifiable 3D printed augmentations (ie, grips) with a "hot switch" to fit different objects into malleable grips.
* Brainstorming ways to improve design of 3D printable augmentations -- therapists, designers, disabled users all have valid input, how to incorporate all of their work in the design and printing process to create the best devices.
* Have everyone in one room at the same table for each project. The issue is not really the technology but the process/workflow. Have accessibility team involved from the onset versus the after thought. It saves projects money and people headaches.
* Currently contractors are not motivated to fulfill contract requirements for Section 508 compliance. Since most development projects are dependent on external development teams, how can we improve compliance by leveraging contracting types, incentives and other mechanisms to promote accessibility and usability across the federal government.

#### Open Data

* Problem: the nationally-funded AT centers house inventories of technology products.  Each center houses its own silo’d data on the products they have, the kinds of user needs those products fit, etc.  Therefore, advocacy groups can’t create apps/interfaces to draw their constituencies to technology that might meet their needs. Make this data open and formatted in a standard way. Yes -- great idea. Make information about the entire collection of AT and other equipment completely public, so people can request demos and loaners and the program becomes self-documenting. Also, involve the vendors in this, because they are motivated to get info out in order to make a sale. Look at the example of [GARI](http://www.gari.info/) from the mobile mfrs.

#### Everyday Web

* Google’s Automatic Captions service makes captioning easy  Problem is, the instructions for using the tool are complicated & the user experience is cumbersome.  The instructions and UX should be more stream-lined. (+1 to this! I’ve never gotten this to work!)
Could [Hyperaud.io](http://hyperaud.io/tour/) help? ([Hyperaud.io code on GitHub](https://github.com/hyperaudio)
* Video: YouTube is not fully accessible, what kinds of tools/products can be used to host these videos fully accessible. Drupal’s modules could be helpful.
* How do you design better experiences for senior citizens? (Related: [News for Betty](http://melodykramer.github.io/2015/03/18/good-news-for-news-for-betty/))
* Make News for Betty better by fixing bugs or adding features.

#### Images on Twitter/Social Media ([Discussed further in this hackpad](https://hackpad.com/Accessible-Twitter-Images-xa5bMHVNJ3N))

* Images often contain blocks of text to bypass 140 character limit
* Twitter does not allow images to contain alt tags
    * Can Descriptive text be embedded in the file itself? (a la steganography?) ([gist](https://gist.github.com/DavidGinzberg/c92dc82a0d3e1bbac3e9))
        * See EasyChrip it allows providing alt text.
    * Does twitter recompress images and remove extra content, though?  Yes, they do (confirmed).
* Images that explain more content for social media/ and What about GIFs?
* Possible to OCR? Use browser plugin to improve Twitter accessibility?
* Image descriptions can be hard for folks with chronic illness/energy management--can be a choice between making a post with no image description (inaccessible) or not posting anything at all. Ways to make image descriptions easier to create?
    * How about crowd-sourced image captioning/description along with a browser plugin to fetch the result when viewing the image?
    * Could you use the [NYTimes Hive platform](http://madison.nytimes.com/contribute/#/find) to crowdsource this in some way?
* Twitter now supports video -- this is a similar challenge

#### Policy

* Standardized testing processes for defining accessible content is needed.
* A way for agencies to share testing results without vendors freaking out.
* Standardization for e-learning accessibility content is needed.
* Mandatory funds need to be available for captioning of multimedia products at every agency.
* The FDA requires that food labels show what companies put inside the food we buy.  Similarly, technology products should label the types of user needs that have been tested in the process of developing technology products.  If a company has NOT tested for the user needs of people with disabilities, then consumers can steer their tech budgets AWAY from those products and toward other products.  Something along the lines of the Voluntary Product Assessment Templates.  Problem is that the VPAT is very subjective, only pertains to 508, and doesn’t ask about whether the product was TESTED with users with specific user needs..
* A lot of federal purchases (~$50B/yr; ~10% of federal purchases) are made via ’schedules’ -- lists of pre-approved products any federal employee can buy without needing to do any paperwork. This means that vendors are strongly motivated to get their products on a schedule. If the schedule process required the highest degree of 508 compliance, vendors might make the extra effort. (I don’t know how much ICT flows through schedules.) (More info: [For Vendors - Getting on Schedule](http://www.gsa.gov/portal/content/198473) )

#### Education

* Students are not taught accessibility concepts in Computer Science classes in colleges and universities. (+1)
* There’s no [certification process](http://webaim.org/blog/accessibility-certification/) for web developers like there is for individual websites.
    * The industry as a whole generally doesn’t trust developer certifications.
        * Depends on the cert. A+? Yeah, not really much going on there. CCNA? RHCE? Those are trusted. The org behind it matters.
* Problem: Too many development/design teams don’t know WHAT 508 is (much less how to develop within its guidelines), even though it has been around for years.  There should be better mechanisms for spreading awareness of 508 and knowledge about and how to build to 508 standards. Make this a tool rather than just another text resource on the web. include online training with badges; create communities of practice to share specific types of solutions.
* Finding ways to expedite on-boarding therapists and disabled users in 3D printing and modeling for designing assistive augmentations -- often it is believed that this takes at least a year or more to learn and to work with assistive devices.  Is there a way to break down barriers and help those who need it learn to use 3D printing hardware and software quickly to begin assistive design work? Also consider how to provide access to 3D printers for these uses, even shared through libraries, engineering schools, etc.
    * see IAAP ([International Association for Accessibility Professionals]( http://www.accessibilityassociation.org/) -- yes, they have a Professional Development Committee, and are oriented towards certification. New org, looking for members; first conference Oct 14-16.

#### Resources

* Add articles/documentation to [A11y Project](https://github.com/a11yproject/a11yproject.com) for better accessibility documentation.
* We need e-learning accessibility courses (including for individuals with disabilities) to help improve accessible content.
* There is an international effort to create a DeveloperSpace (part of GPII)  that would include not only code and tools but communities of users and RESOURCES that are written in a format that is directly usable by people who are developing (AT and Mainstream) -- and also can connect them to other users.  But how do we best do that.  Easy to define the need - hard to deliver things that are concise and usable to busy developers.
* Problem: folks who advocate for 508-compliant websites within their organizations lack good guidance/tools for making arguments/business cases within their organizations to invest in changes to the website to align with 508.  WAI has some good materials, but maybe there needs to be a specific resource for feds, using the issues that motivate public sector agencies.

#### Misc - Need to be grouped.

* Problem: people who may not have reliable memory or biometrics have trouble authenticating into information systems.
* Problem: some assistive tech can be perceived as malware (because it collects keystrokes, etc).
* Problem: it’s hard to identify the Wikipedia articles related to accessibility and the quality of them.  It would help to have an interface that identifies accessibility-related Wikipedia articles that could use work, or fill-in conceptual gaps, etc.  This would inform advocates and others.

### Projects?

#### Accessibility Crawler-Reporter ("Tattle-Tool")

* mentioned by Gregg V. for finding un-captioned videos on a site or domain or beyond
* could also look for videos without description, PDFs that are scans or otherwise inaccessible
* very useful to help agencies manage their accessibility programs -- locate the video; notify both the uploader (via system logs?) and the a11y program manager.
* also useful to external organizations such as advocacy orgs.
* tool could be extended to route file to a remediation service; point author to learning resources and tools

#### Accessibility Requester

* lets a user who encounters a specific a11y problem to request remediation, like an un-captioned video or inaccessible PDF. this is better than a note to a webmaster -- it would trigger queueing and agency management of the issue.
* in some situations having a visible count of requests might help build the overall audience argument -- "OMG there are 30 people asking for us to caption this" and viral effects.

#### Notes / Links

* [Steve Jacobs Lightning talk](http://www.ideal-group.org/ld/)

### Policy Hack Hackpad: [Policy Hack](https://hackpad.com/Policy-Hack-tJgZezcu1bB)

### Announcements:

* Hi ... Happy Hour Tomorrow Evening (April 1st at 6 pm) at Clyde’s of Gallery Place - Chinatown on topic of [accessibility as an innovation process](http://www.meetup.com/dc-Accessibility-Innovation-Meetup/events/221187195/) - to promote entrepreneurship, innovation, etc ... very first meetup for us so we want to see what direction we can take.

### Hackathon Projects:

* [Section 508 Procurement Playbook](https://github.com/18F/508-procurement-playbook)
* Procurement Plays
    * Software Development Contracts
        * In the RFP process, integrate accessibility as an evaluation factor
            * Determine weight in relation to other criteria
        * Identify accessibility specifications for each project and spell out the accessibility requirements
        * Reference Section 508 as the standard, but also integrate feedback from users and project owners
        * Identify user population and specific user requirements (i.e. will the VAs user pop be the same as GSAs)
        * Require contractors to submit a VPAT and examples of Section 508 compliant work in their past performance
    * In the evaluation process, review for Section 508 knowledge and past performance
    * In the award process, tie payment to accessibility attestation by a third party
        * Awards should include requirements to involve a third party accessibility compliance contractor for testing and reporting
        * This should be done in conjunction with existing sprint schedules and regular testing
        * Incentive payments for accessibility or accessibility CLINs should be released only after final certification by the third party
    * COTS
        * In the RFP process state specific standards for accessibility
        * Tie release of payment to attestation by a third party tester
            * Once software has been tested, that version will remain in a centralized database and can be referenced by other contracting offices
        * For name brand specific procurements CORs are required to research section 508 compliance during the market research phase and provide a summary to COs.
    * Hardware
        * Agency IT offices in conjunction with Section 508 offices should establish standard language for hardware categories
        * In the RFP process explicitly state specific standards for accessibility
        * Ensure that hardware being purchased has the capacity to accommodate accessibility software
