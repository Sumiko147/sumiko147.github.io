# Sumiko Mitchell | CS-499 Computer Science Capstone
## ePortfolio | Southern New Hampshire University
---
## Code Review
The code review below provides a walkthrough of the Travlr Getaways 
application prior to enhancement. It covers the existing functionality 
of the codebase, identifies areas for improvement across structure, 
logic, security, and efficiency, and outlines the planned enhancements 
for each of the three ePortfolio categories: Software Design and 
Engineering, Algorithms and Data Structures, and Databases.

[Watch the Code Review on YouTube](https://youtu.be/NoSrbMSOoqA)

---
## Enhancement One: Software Design and Engineering
[View Original Artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Capstone_Initial) | [View Enhanced Artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Enhancement_One)

Travlr Getaways is a full-stack travel booking application developed 
during CS-465 at SNHU. It is built on the MEAN stack with Passport.js 
for authentication and jsonwebtoken (RFC 7519) for token-based 
authorization.

This enhancement adds role-based access control to an application that 
previously authenticated users but did not distinguish between roles. 
A two-tier system introduces admin and subadmin roles, where subadmin 
permits record updates without granting creation or deletion rights. 
This design reflects the principle of least privilege and was informed 
directly by a permission bottleneck observed in a production environment 
at work.

Course Outcomes 4 and 5 were met: JWT role claims enforce access control 
without additional database queries, and distinct 401 and 403 responses 
reflect deliberate security design. The role-based foundation is 
structured to support a dedicated user management interface as a 
natural next step.

---
*Additional sections coming soon: Enhancement Two (Algorithms and Data 
Structures), Enhancement Three (Databases), and Professional 
Self-Assessment.*
