# WORKSHEET 2
## Identify Objects, Classes, and Relationships

**Instructions:** Use the process and proposed system from Worksheet 1 to complete this worksheet.

---

## Part 1. Identify the Objects

Identify the important people, things, records, transactions, or concepts that your proposed system needs to represent.

**Guide Question:**

If you were going to create a program for this process, what things would the program need to represent?

| No. | Object | Description |
|:---:|---|---|
| 1 | Class | Where students are taught lessons by their assigned teacher |
| 2 | Students | Students of each class |
| 3 | Adviser | The homeroom adviser of each class |
| 4 | Subject_Teacher | Specific teacher per subject of each class. |
| 5 | Attendance_Sheet| To check the attendance of the students in each class. |
| 6 | Class_Monitor| The person that monitors and updates the attendance of students |


### Object Evaluation

For each identified object, ask:

- Does it play an important role in the process?
- Does it contain information?
- Does it perform an action?
- Does it interact with another object?
- Does the proposed system need to keep track of it?

**Reminder:** Remove objects that are not necessary for your proposed system.

---

## Part 2. Analyze Object Interactions

Determine how your identified objects interact with one another.

**Example:** `Student → submits → Request`

| No. | Object 1 | Interacts | Object 2 |
|:---:|---|---|---|
| 1 | Class_Monitor | updates | Attendance_Sheet |
| 2 | Subject_Teacher | confirms | Attendance_Sheet |
| 3 | Adviser | checks | Attendance_Sheet |
| 4 | Class_Monitor | tracks | Students |

---

## Part 3. Identify Possible Classes

Determine which objects can become classes in your proposed system.

Not every object needs to become a class. Choose only the objects that are important to your proposed system.

| No. | Class | What does it represent? |
|:---:|---|---|
| 1 | Students | Represents the individuals that have their attendance confirmed and monitored |
| 2 | Subject_Teacher | Checks and confirm the students’ attendance |
| 3 | Class_monitor | Checks and monitors their fellow students' attendance |
| 4 | Attendance_Sheet | The attendance sheet in which every class is given |
| 5 | Adviser | The Homeroom Adviser for each class |
| 6 | Class | The place where everyone belongs |

---

## Part 4. Class Analysis

Analyze the attributes and methods of each identified class.

### Class No. 1

**Class Name:** __________________________________

**Purpose:**  
__________________________________________________

#### Attributes

| Attribute | Description |
|---|---|
| | |
| | |
| | |
| | |

#### Methods

| Method Name | What does it do? |
|---|---|
| | |
| | |
| | |
| | |

---

### Class No. 2

**Class Name:** __________________________________

**Purpose:**  
__________________________________________________

#### Attributes

| Attribute | Description |
|---|---|
| | |
| | |
| | |
| | |

#### Methods

| Method Name | What does it do? |
|---|---|
| | |
| | |
| | |
| | |

---

**Additional Classes:** Add another copy of the Class Analysis section for each additional class you identify.

**Reminder:** Keep your project simple. Avoid creating unnecessary classes.

---

## Part 5. Identify Class Relationships

Determine how your identified classes are related to one another.

| No. | Class 1 | Relationship | Class 2 | Why are they related? |
|:---:|---|---|---|---|
| 1 | Teacher | Association | Student | The teacher has many relationships with many students  in their class by checking and confirming their attendance |
| 2 | Class_Monitor | Inheritance | Student | The class monitor is a specialized version of a student, but with specific duties |
| 3 | Teacher | Inheritance | Subject_Teacher | The subject teacher is a specialized version of a teacher, but the teacher is assigned to a specific subject. |
| 4 | Class_Monitor | Association | Attendance_Sheet | The class monitor interacts with the attendance sheet by monitoring and updating the attendance of students using the attendance sheet. |

### Relationship Types

| Relationship | Description |
|---|---|
| **Association** | Two classes interact with one another. |
| **Aggregation** | One class groups or contains objects that can exist independently. |
| **Composition** | One class strongly owns another object. |
| **Inheritance** | One class is a specialized version of another class. |

**Reminder:** Use only the relationship types that make sense for your proposed system. Not all relationship types are required.
