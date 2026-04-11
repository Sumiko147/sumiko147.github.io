# Sumiko Mitchell  
## CS-499 Computer Science Capstone  
### ePortfolio | Southern New Hampshire University  

---

This ePortfolio highlights my work in full-stack web development, with a focus on secure application design, efficient data handling, and database-driven decision-making.

**Technologies:** Node.js · Express · MongoDB · Angular · Passport.js · JSON Web Tokens

---

## Featured Artifact: Travlr Getaways  

Travlr Getaways is a full-stack travel booking application developed during CS-465 at SNHU. It is built on the MEAN stack (MongoDB, Express, Angular, Node.js) and supports both a public-facing website and an administrative interface.

This application serves as the foundation for all enhancements in this portfolio, demonstrating progressive improvements across software design, algorithms and data structures, and database functionality.

---

## Code Review

This code review presents a walkthrough of the Travlr Getaways application prior to enhancement. It identifies key opportunities for improvement in structure, logic, security, and efficiency, and outlines planned enhancements across software design, algorithms, and database functionality.

[Watch the Code Review on YouTube](https://youtu.be/NoSrbMSOoqA)

---

## Enhancement One: Software Design and Engineering  

**Artifacts**  
View the [original artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Capstone_Initial) | [enhanced version](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Enhancement_One)

---

**Context**  
This enhancement builds on the Travlr Getaways application by introducing role-based access control to a system that previously authenticated users without distinguishing between roles.

**Enhancement**  
A two-tier role system was implemented, including admin and subadmin roles. The subadmin role allows updates to existing records without granting creation or deletion permissions. This design follows the principle of least privilege and was informed by a real-world permission bottleneck observed in a production environment.

**Course Outcomes**  
Course Outcomes 4 and 5 were met through the implementation of JWT role claims to enforce access control without additional database queries. The deliberate use of 401 and 403 status codes reflects a clear and intentional security design. This role-based foundation is structured to support a dedicated user management interface as a natural next step.

---

## Enhancement Two: Algorithms and Data Structures  

**Artifacts**  
View the [original artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Capstone_Initial) | [enhanced version](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Enhancement_Two)

---

**Context**  
This enhancement extends the Travlr Getaways application by introducing dynamic, multi-criteria sorting of trip data.

**Enhancement**  
Sorting functionality was implemented at the database level using MongoDB’s native sorting capabilities, allowing users to sort trips by price, start date, and rating. Query parameters are mapped to corresponding database fields, enabling flexible and efficient data retrieval through the API.

Additional improvements included correcting data types within the schema to ensure accurate sorting behavior for numeric and date fields. Moving sorting to the database layer reduces client-side processing and improves scalability as the dataset grows.

**Course Outcomes**  
Course Outcome 3 was met through the design and evaluation of an algorithmic solution that balances performance and scalability. Moving sorting to the database layer reflects a deliberate design choice that minimizes client-side overhead and leverages database optimization.

Course Outcome 4 was reinforced through the use of MongoDB’s native query capabilities and efficient handling of query parameters within the API. Instructor feedback highlighted the effectiveness of this approach and identified indexing as a future enhancement to further improve query performance.

---

## Enhancement Three: Databases  

**Artifacts**  
View the [original artifact](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Capstone_Initial) | [enhanced version](https://github.com/Sumiko147/cs465-fullstack/tree/CS499_Enhancement_Three)

---

**Context**  
This enhancement builds on prior work by introducing database-driven reporting capabilities to support administrative decision-making.

**Enhancement**  
MongoDB aggregation pipelines were implemented to generate summary statistics and grouped reporting data for the admin dashboard. One pipeline calculates total trips, pricing statistics, and average ratings, while another groups trips by month using ISODate values.

These pipelines execute concurrently using Promise.all, improving performance by avoiding sequential database calls. The results are exposed through a protected API endpoint and displayed in an Angular dashboard designed for non-technical users.

The data model was also improved by introducing a structured numeric rating field, populated through a migration script that extracts values from existing string data. Validation is enforced at both the schema and application levels to ensure consistency. This enhancement strengthens the application’s ability to support data-driven decision-making through efficient aggregation and clear presentation of reporting data.

**Course Outcomes**  
Outcome 1 was met by designing a dashboard that communicates complex data clearly to non-technical users, supporting organizational decision-making.

Outcome 2 was met through the structured presentation of data and well-documented aggregation logic, ensuring both usability and maintainability.

---

### Upcoming Enhancements

A professional self-assessment will complete the portfolio by reflecting on technical growth and career direction.

---

