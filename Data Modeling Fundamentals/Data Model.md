# What is a Data Model
- Data modelling is the process of visualizing and representing data for storage in a DB.
- A blueprint of the business concepts, the relationships and the rules between them
- Failure to Data Model results in poor Data Quality
# Modeling Techniques
1. OLTP
   - Focuses on real-time execution of large numbers of DB transcations
   - Handles daily transactions or operations
2. OLAP
   - Focuses on analysis at high speeds on large volumes of data
   - Supports business decision making
# Types of Data Models
1. Conceptual Data Model
   - A high-level perspective business concepts and the relationship between them
   - Nontechnical
   - Objective is to provide current and future state of data concept for the organization
     
     <img width="417" alt="Screenshot 2025-02-09 at 12 08 09 am" src="https://github.com/user-attachments/assets/c1dd72fa-450f-4de3-9ab1-3fd386751bf5" />

2. Logical Data Model
   - Transitions business concepts into data entities
   - Database agnostics

     <img width="475" alt="Screenshot 2025-02-09 at 12 09 21 am" src="https://github.com/user-attachments/assets/c038dea3-e7be-409d-8ad7-2f6b261a6393" />

3. Physical Data Model
   - DB specific design that represents the data objects and their relationships
   - Generate DDL code that would be deployed to a database platform

     <img width="497" alt="Screenshot 2025-02-09 at 12 11 55 am" src="https://github.com/user-attachments/assets/5270f3b1-4121-45e8-b101-4bb702e0eefb" />

# Basic Components of a Data Model
1. Entity (Logical) / Table (Physical)
   - A singular representation of a distinguishable thing, event or state
2. Attribute (Logical) / Column (Physical)
   - Individual piece of information for eact entity or table
3. Relationships
   - Connects two entities or tables
