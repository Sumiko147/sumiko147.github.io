# Sumiko Mitchell  
## CS-499 Computer Science Capstone  
### ePortfolio | Southern New Hampshire University  

---

This ePortfolio highlights my work in full-stack web development, with a focus on secure application design, efficient data handling, and database-driven decision-making. The featured artifact, Travlr Getaways, demonstrates my ability to evaluate, enhance, and communicate real-world software solutions using industry-standard tools.

**Technologies:** Node.js · Express · MongoDB · Angular · Passport.js · JSON Web Tokens

---

## Code Review

This code review presents a walkthrough of the Travlr Getaways application prior to enhancement. It identifies key opportunities for improvement in structure, logic, security, and efficiency, and outlines planned enhancements across software design, algorithms, and database functionality.

[Watch the Code Review on YouTube](https://youtu.be/NoSrbMSOoqA)

---

## Enhancement One: Software Design and Engineering  

[View Original Artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Capstone_Initial)  
[View Enhanced Artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Enhancement_One)

---

**Artifact Overview**  
Travlr Getaways is a full-stack travel booking application developed during CS-465 at SNHU. It is built on the MEAN stack and uses Passport.js and JSON Web Tokens (RFC 7519) for authentication and authorization.

**Enhancement**  
This enhancement introduces role-based access control to an application that previously authenticated users without distinguishing between roles. A two-tier system defines admin and subadmin roles, where subadmin permissions allow updates without granting creation or deletion rights. This design follows the principle of least privilege and was informed by a real-world permission bottleneck observed in a production environment.

**Course Outcomes**  
Course Outcomes 4 and 5 were met through the implementation of JWT role claims to enforce access control without additional database queries. The deliberate use of 401 and 403 status codes reflects a clear and intentional security design. This role-based foundation is structured to support a dedicated user management interface as a natural next step.

---

### Upcoming Enhancements

Enhancement Two will focus on algorithmic efficiency through multi-criteria sorting.  
Enhancement Three will introduce database-driven reporting using MongoDB aggregation pipelines.  
A professional self-assessment will complete the portfolio by reflecting on technical growth and career direction.

---

