# gaming-room-design
 Software Design Document for The Gaming Room - CS230 Portfolio Submission 
# CS 340 Portfolio Reflection

## How do you write programs that are maintainable, readable, and adaptable?
In this course, I focused on making my code modular and reusable. For example, in Project One I built a **CRUD Python module** to connect the dashboard to the MongoDB database. By separating the CRUD operations into their own module, I avoided duplicating code and made the logic easier to maintain. The functions had clear names, docstrings, and consistent formatting, which improved readability. The biggest advantage was adaptability: I was able to reuse the CRUD module in Project Two to power multiple dashboard widgets without rewriting my database logic. In the future, this same CRUD module could be repurposed for other applications that need database access, such as different dashboards or web apps.

## How do you approach a problem as a computer scientist?
When I approach a problem, I try to **break it down into smaller, testable parts**. With Grazioso Salvare’s requirements, I started by identifying the database needs and creating queries to pull the right data. Then, I worked on displaying that data visually through widgets in the dashboard. Compared to past assignments, this project required more planning and integration across multiple parts — database design, Python modules, and visualization. I also used testing and iteration to confirm that the CRUD functions and dashboard outputs were correct. In future projects, I would use a similar strategy: gather requirements, design modular solutions, and validate each part before combining them into the final system.

## What do computer scientists do, and why does it matter?
Computer scientists solve problems by creating systems that turn raw data into useful information. In this project, my work would help Grazioso Salvare track and analyze animal shelter data more efficiently, allowing them to identify dogs for rescue training more effectively. That efficiency can make a real difference in saving lives. More broadly, computer scientists create tools that help organizations work smarter, automate repetitive tasks, and make informed decisions. The ability to take data, design a solution, and deliver actionable insights is what makes the work valuable to companies and communities.
