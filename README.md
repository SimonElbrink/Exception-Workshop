# Workshop: Exception Handling

In this workshop, you will work with a program designed to read strings from three different files containing:
- **Male first names**
- **Female first names**
- **Last names**

The program includes a save feature to make your changes persistent. The purpose of this workshop is to build a library of names that you can use to **seed random male and female names**, which can be helpful when creating multiple objects.

---

## Objective
Your task is to handle the **checked exceptions** that are intentionally left unhandled in the `CSVReader_Writer` utility class.

---

## Requirements

1. **Handle exceptions with different approaches:**
    - At least one method should be handled using **try-catch-finally**.
    - At least one method should use **try-with-resources** with a catch block.
    - At least one method should declare a `throws` clause, which must be handled at the method invocation.

2. **Custom exception:**
    - Create a custom exception for the `add` methods in the `NameService` class.
    - This custom exception should be thrown when attempting to add a name that already exists.
    - Handle this exception with a friendly error message.

3. **Random person creation:**
    - Successfully create an object of type `Person` using the method `getNewRandomPerson`.

4. **Saving names:**
    - Ensure that any new names added to the lists can be saved back to the files.

---

## Constraints

> **You may not:**
> - Declare a `throws` clause in the `static void main` method.
> - Refactor the code to avoid exception handling. (This workshop is focused on practicing exception handling! 😊)

---

## Checklist

- [ ] Use **try-catch-finally** to handle an exception.
- [ ] Use **try-with-resources** with a catch block for exception handling.
- [ ] Handle a method with a `throws` clause at its invocation.
- [ ] Implement and handle a **custom exception** in the `NameService` class.
- [ ] Create a `Person` object using `getNewRandomPerson`.
- [ ] Save newly added names to the files successfully.

---

> Once you complete the workshop, feel free to refactor the code as desired.
> 
**Good luck and happy coding!**
