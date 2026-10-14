# Assignment #4: Forms and Validation

**Student Name:** Akshit  
**Group:** IT-2504  
**University:** Astana IT University  

---

## Project Objectives
The objective of this assignment is to design clean, accessible web forms using native HTML5 capabilities alongside structural styling classes from the Bootstrap framework. Additionally, it implements frontend validation using integrated HTML5 elements and dynamic CSS feedback layers from Bootstrap 5.3.

---

## Assignment Parts and Implementation

### Part 1: Basic HTML Forms
#### Task 0: Simple Contact Form & Task 1: Form with HTML5 Validation
- Implemented a vanilla HTML structure containing explicit mappings between `<label>` items and input controls (`<input>`, `<textarea>`) via unique ID binders.
- Configured programmatic data enforcement constraints utilizing structural attributes including `required`, `type="email"`, `minlength`, and `maxlength`.
- **Placeholder for Screenshot:**  
  *Task 0 & 1 Runtime Verification Snapshot*  
  ![Part 1 Form Screenshot](screenshot_part1.png)

---

### Part 2: Bootstrap Forms
#### Task 2: Bootstrap Form Styling & Task 3: Bootstrap Validation Styles
- Migrated the baseline fields into a Bootstrap 5 card view using layout blocks like `.mb-3` and target element definitions like `.form-control` or `.form-label`.
- Configured dynamic interaction indicators via `.valid-feedback` and `.invalid-feedback` text elements linked to runtime CSS checks.
- Bound a client-side execution interception script that cycles through `.needs-validation` forms on trigger and maps structural classes like `.was-validated` onto form scopes.
- **Placeholder for Screenshot:**  
  *Task 2 & 3 UI & Validation Feedback Snapshot*  
  ![Part 2 Form Screenshot](screenshot_part2.png)

---

### Part 3: Advanced Form Project
#### Task 4: Registration Form
- Created a fully responsive profile registration interface structured via Bootstrap Grid containers (`.row`, `.col-md-6`).
- Integrated diverse interaction components including structural radio lists (`.form-check-inline`), multiple-selection checkboxes, and selective dropdown configurations (`.form-select`).
- Added manual JavaScript logic triggers within the event listener engine to programmatically cross-reference string equivalence matches between password inputs (`#password` and `#confirmPassword`).
- **Placeholder for Screenshot:**  
  *Task 4 Full Registration Screen Responsive Check*  
  ![Part 3 Form Screenshot](screenshot_part3.png)

---

## Brief Summary of Work Process
1. **Design Structuring Phase:** Formulated core field components using semantic elements, making sure input elements map cleanly to corresponding form labels.
2. **Framework Integration Phase:** Integrated Bootstrap 5 library templates via target Content Delivery Network references to layout a grid layout framework.
3. **Validation Mapping Phase:** Configured built-in validation rules and implemented a JavaScript event tracking loop to capture submit states, toggle contextual feedback, and perform password matching checks.
4. **Testing Phase:** Tested edge cases including syntax mismatches, blank field submissions, and layout transitions across responsive desktop and mobile viewports.
