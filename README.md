# Open Source Projects for College Students
The purpose of this repository is to compile a list of resources and accessible open source projects for college students and recent graduates who are looking to develop a code portfolio to show to potential employers.  Please feel free to add to/update this list and to invite others who may be interested in contributing.

Projects
==

**Advising app** (https://github.com/jschanker/molloy-advising-web-application: can try it out at https://www.googledrive.com/host/0B4vQqEpEVGSHWU14eFVycjEwQUE): This is currently written for Molloy College's requirements, and the code needs to be cleaned up a lot.  By selecting all and copying/pasting the course history from Lions Den, it will identify the courses you took and filter out the extraneous details.  It will then answer questions such as: Do you need to take a prerequisite for Calculus III to graduate on time? Are you on pace with your general education or major requirements?  If you were to change your major, how many more credits would you need? What classes are available this semester, and how would taking them impact your progress? Do you need a given course and do you have its prerequisites?

Students are working on a new version of this in which they are cleaning up the code and also attempting to have it determine schedules that will maximize overall student satisfaction.  See: https://github.com/Cosias/courseRegistration

**Online mentoring app** (https://github.com/zach111694/onlineMentoring): Taking an interest in the well-being of someone who you only just met can make a huge difference in that person's life, particularly when that individual doesn't have many people who look out for him/her.  This could help explain why mentoring can be so successful for economically disadvantaged youth.  Unfortunately, there is a shortage of volunteers.  It is our hope that an online mentoring app would preserve the benefits of mentoring while making people more likely to volunteer as mentors.  This app is meant to facilitate this communication and to attempt to maximize total mentor/mentee satisfaction over all pairs through questionaires and other compatibility metrics.  This requires a number of algorithms to be written: e.g., one to determine appropriate point values for questions through the gathering of data and one to maximize the total among all possible pairs once the point values between pairs is assigned.  (More details to be filled in later)

**Ruby Text2Code** (https://www.github.com/jschanker/ruby-text2code): This is a project that's being supported by a Google grant.  The Text2Code library stretches the flexibility of the Ruby programming language to allow a user to type in English statements (with spaces!) that closely resemble the text on Blockly's code blocks.  Blockly allows you to drag and drop blocks of code and have these code blocks translated into instructions in popular programming languages such as Python and JavaScript. See: https://blockly-demo.appspot.com/static/demos/code/index.html for a demo of Blockly.  One of the educational objectives of Blockly is to allow a person new to programming to focus on the logic of getting a computer to solve problems without worrying about the syntax.  The purpose of the Ruby Text2Code library is to help transition people from Blockly to Ruby.  Unfortunately, stretching the capabilities of Ruby is not without its downsides and syntax can wind up becoming an issue because of this.  Parentheses often need to be added in places in which you wouldn't expect to need them and syntax errors can be harder to spot.  To achieve the intended goal then, it would help to create an IDE that would allow new users to identify these errors by pointing them out in an understandable way and by automatically correcting some of them.

**Original Text2Code** (https://github.com/jschanker/text2code): Rather than running instructions directly, the original Text2Code would attempt to convert English statements in a certain form to Blockly code blocks, which would then be translated into Python and JavaScript.  The generated JavaScript code would then be run.  See: https://www.googledrive.com/host/0B4vQqEpEVGSHTGl1N1doSjl4S1U for a demo.

**Molloy Virtual World Scrabble** (https://github.com/jschanker/molloy-virtual-world-scrabble): This is an interdisciplinary project with English, Art, and Music.

**Molloy Life App** (https://github.com/zach111694/molloyLife and https://github.com/MolloyLifeMedia/molloyLifeMedaBackend): The Molloy Life app aggregates data about on-campus student organizations, events, and other information of interest to Molloy students and displays it in a mobile friendly way.  See http://dev.molloylife.com.

Resources
==
**HTML/CSS**

*Head First HTML and CSS* by Elisabeth Robson and Eric Freeman, O'Reilly Media; 2nd edition (September 8, 2012), ISBN-13: 978-0596159900 : A beginners book for learning HTML and CSS

**JavaScript**

*Head First JavaScript Programming* by Eric T. Freeman and Elisabeth Robson, O'Reilly Media; 1st edition (April 10, 2014), ISBN-13: 978-1449340131 : A beginners book for learning JavaScript and programming in general

*Eloquent JavaScript* (http://eloquentjavascript.net): A comprehensive free online book for learning JavaScript (includes the basics of Node.js)

*Professional JavaScript for Web Developers* by Nicholas C. Zakas, Wrox; 3rd edition (January 18, 2012), ISBN-13: 978-1118026694 : Has helpful and terse explanation of prototype-based programming in JavaScript with diagrams.

**C++**

*The C++ Programming Language* by Bjarne Stroustrup, 4th Edition : Textbook written by the creator of C++ himself.

*A Computer Science Tapestry* by Owen L. Astrachan, McGraw Hill, 2nd Edition (1999):  Book is now out of print and made freely available by its author at: https://www.cs.duke.edu/csed/tapestry/computersciencetapestry.pdf

**Interview Questions**

https://github.com/kennyyu/workshop/blob/master/problems.pdf

https://github.com/h5bp/Front-end-Developer-Interview-Questions

**Knowledge Areas**

Google's Technical Development Guide: https://www.google.com/about/careers/students/guide-to-technical-development.html

ACM Computer Science Curricula 2013: https://www.acm.org/education/CS2013-final-report.pdf
