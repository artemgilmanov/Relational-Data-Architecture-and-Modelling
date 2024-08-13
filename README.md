# Pizza Shop Database Project

We have been asked by the owner of three local pizza shops to set up a simple database to use to run the business.

The owner wants to track customers' pizza orders to ensure the staff completes and delivers the best pizza. In doing so, the owner wants to set up better tracking of the shop's sales.

---

## What is a Conceptual Model?

A conceptual model is a simplified representation of the final database. The focus is on the broad picture, and specifics are removed.

### Key Features of a Conceptual Model

- Define business needs
- Establish vocabulary
- Foster communication
- Build a plan for favorable outcomes

### Steps to Build a Conceptual Model

1. Identify business objects
2. Establish relationships between objects
3. Determine cardinality
4. Name the relationship
5. Repeat as necessary

---

## What is a Conceptual Model Entity?

- Loosely speaking, you can think of model entities as database tables.
- Think of them as "nouns."
- They are the starting point for our database table design.

---

## Cardinality and Crow's Foot Notation

### Cardinality Types:

- **One**
- **Many**
- **One or Many**
- **One and Only One**
- **Zero or One**

![Cardinality and Crow's Foot Notation](images/cardinality.png)

### Example Relationships:

- **One to One**: `Person` owns `Passport`  
  ![One to One](link-to-image)

- **One to One (Mandatory)**: `Mother` raises `Child`  
  ![One to One (Mandatory)](link-to-image)

- **One to Many**: `Customer` places `Order`  
  ![One to Many](link-to-image)

- **Many to Many**: `Teacher` teaches at `School`  
  ![Many to Many](link-to-image)

---
