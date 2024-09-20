# Project-management-system
This project is a comprehensive Project Management System developed using Object-Oriented Programming (OOP) concepts in Python. It provides functionality for creating, updating, and deleting projects, tasks, and team members and can be applied across various industries, including software development, construction, and event planning.
# Key Features:
OOP Principles:
Encapsulation: Each class has private attributes, accessed only via getter and setter methods, ensuring data protection.
Abstraction: The TaskABC class serves as an abstract base class, providing a blueprint for the Task class, which must implement the complete_task and update_task methods.
Inheritance: Classes like DevelopmentTask, DesignTask, and ConstructionProject inherit from base classes, promoting code reuse and organization.
Polymorphism: The add_task and add_team_member methods in the Project class accept different types of objects, allowing flexibility in task and team member management.
# Algorithms:
The project incorporates optimized searching and sorting algorithms, such as binary search, bubble sort, and quick sort, to efficiently manage tasks and projects. Computational complexities of these algorithms are explained, highlighting their effectiveness in different scenarios.
# Project Structure:
Core classes include:
Project: Manages the overall project lifecycle, including tasks and team members.
Task: Represents individual tasks that must be completed within a project.
Team Member: Manages the team members associated with the project.
Testing:
The project includes various testing methods to ensure that the system functions properly. This guarantees that the features and algorithms work as expected in different scenarios.
Overall, this project offers a robust, OOP-based project management tool that leverages Python’s features for effective task and team management, underpinned by optimized algorithms for performance.
