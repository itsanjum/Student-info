//
//  README.md
//  
//
//  Created by Anjum Unnisa on 04/12/24.
//
# Student Information

This project demonstrates how to store and display information about a student using a simple JavaScript object.

## Code Details

The project includes the following features:
- A `Student` object with the following properties:
  - `name`: The student's name.
  - `phone_number`: The student's phone number.
  - `marks`: The student's marks.
- Console logs to display the student's details.

### Code Example:
```javascript
const Student = {
    name: "Anjum",
    phone_number: "8073801279",
    marks: 79
};

console.log("Student Detail of " + Student["name"]);
console.log("Name: " + Student.name);
console.log("Phone Number: " + Student.phone_number);
console.log("Marks: " + Student.marks);
