# Student Class Project

This repository contains a Java class `Student` that represents students with attributes such as name, major, student ID, and GPA. The class also provides a method to display the student's information.

## Class Structure

### Attributes:
- **`name`** (String): The student's name.
- **`major`** (String): The major or field of study the student is pursuing.
- **`ID`** (int): A unique identifier for each student.
- **`GPA`** (Double): The grade point average (GPA) of the student.

### Methods:
- **`Student(String name, String major, int ID, Double GPA)`**: A constructor that initializes the student's details when an object is created.
- **`displayInfo()`**: This method prints the student's name, major, ID, and GPA.

### Example Usage:
In the `main()` method, we create three instances of the `Student` class and display the information for each student.

```java
public static void main(String[] args) {
    Student student1 = new Student("Aiturgan", "Data Science", 5555555, 3.7);
    Student student2 = new Student("Saikal", "Management in IT", 18915, 2.0);
    Student student3 = new Student("Duulat", "Comp Math", 2310508, 4.0);

    student1.displayInfo();
    System.out.println();
    student2.displayInfo();
    System.out.println();
    student3.displayInfo();
}
UMl diagrama

![Снимок экрана ](https://github.com/user-attachments/assets/fb938e32-a4bb-4980-bca7-46322b631c67)

