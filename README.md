
<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# QuickFix 

## Basic Details

### Team Name: Warriors

### Team Members
- Member 1: Niya Sabu -College of Engineering Trivandrum
- Member 2: Keerthana K Menon - College of Engineering Trivandrum

### Hosted Project Link
https://tink-her-hack-temp-blue.vercel.app/

### Project Description
Quickfix is a real-time campus complaint management designed to bridge the communication gap between students and administrative maintenance teams.



### The Problem statement
Issues like broken fan,broken light,water leakage etc are not addressed by most of the campus.These are gone unseen and are not found with solutions.To make sure the correct regulation and rectificatiion of these issues we bring to you The Quickfix App

### The Solution
Quickfix provides you:
* A platform to address your concerns and problems
* a way to build social communication and unity
* find the bunch of people having the sam issue as you and upvote if you are facing the same
* you need not to file a new complaint if you are facing the same issue as others ,you can just upvote
* A completely updating leaderboard to promote civic participation in the same

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML,CSS and JavaScript
- Frameworks used:none
- Libraries used:Firebase SDK (Firestore, Hosting)
- Tools used: VS Code,Git and Firebase Console
  
## Features

List the key features of your project:
- Feature 1: Helps in identifying the same issue faced by students by using the upvote button.
- Feature 2:The one issue with the most votes gets the top priority and gets soon resolved
- Feature 3: Gamified leaderboard with points and badges.
- Feature 4: Admin Urgency Tracking: A dedicated "Overdue" sidebar for administrators that highlights complaints that haven't been addressed within the SLA (Service Level Agreement) period.

---

## Implementation

### For Software:

#### Installation
```bash
# Clone the repository
git clone https://github.com/your-username/quickfix.git

#Navigate to project directory
cd quickfix

```

#### Run
Open index.html directly in your browser


## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

https://github.com/KeerthanaKMenon/tink-her-hack-temp/blob/main/Screenshot%202026-02-28%20180500.png(main screen)



#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---


## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---



## Project Demo

### Video
https://drive.google.com/file/d/1_weDCwsCfJX9e_wiHKh77Dpu4M0YHbc2/view?usp=sharing

The video showcases the complete working implementation of QuickFix – Campus Maintenance Portal, highlighting both student and admin workflows along with real-time updates powered by Firebase.
It has dual login system,one for students which can be logged in using studentId and other for admin using password authentication.
Student dashboard views all complaints sorted by priority and we can also file a new complaint.
The demo also highlights the gamified leaderboard system. Students earn points for filing complaints, receiving upvotes, resolving issues, and casting votes. The leaderboard dynamically ranks students based on their total points and assigns badges such as Champion, Top Reporter, Active, and Newcomer. 
The administrators can view all complaints across the campus. Admins can update the status of complaints from Open to In Progress and then to Resolved. The system also displays an overdue sidebar that highlights complaints unresolved for more than ten days, helping administrators prioritize critical issues. 



## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

Niya Sabu: Frontend development, UI/UX design, student dashboard, and leaderboard implementation.
Keerthana K Menon: Backend development, Firebase integration, database design, and admin dashboard functionality.

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
