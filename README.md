<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> An AI-driven educational platform that provides cognitive and behavioral insights by integrating academic performance with psychological assessments to enhance student development.
>
> CognifyEdu aims to streamline the learning process by providing a user-friendly platform for managing assignments, tracking student progress, and offering insightful cognitive and behavioral data. We believe in enhancing the educational experience by empowering teachers, students, and parents with meaningful insights to foster student growth and development.

### User Stories

#### Teacher

- As a teacher, I want to create and assign assignments to my students so that I can assess their understanding of the material.
- As a teacher, I want to view and grade student submissions so that I can provide timely feedback on their work.
- As a teacher, I want to view detailed student profiles, so I can provide targeted support and interventions.

#### Student

- As a student, I want to view my assigned courses so that I can keep track of my assignments.
- As a student, I want to submit my assignments, so I can complete tasks and receive feedback on my performance.
- As a student, I want to receive personalized learning paths, so I can focus on my strengths and areas for improvement.

#### Parent

- As a parent, I want to understand my child’s abilities and development, so I can support their learning at home effectively.
- As a parent, I want to view my child’s cognitive and behavioral insights, so I can monitor their academic and personal development.
- As a parent, I want to ensure my child is engaged in their studies and thriving in their academic environment.

#### Admin

- As an admin, I want to view and manage all users, so I can oversee platform activities and ensure smooth operation.
- As an admin, I want to view and manage courses, so I can ensure the platform’s educational content is up to date and properly organized.
- As an admin, I want to ensure that parents can view their children's profiles and monitor their performance, so they can stay informed about their child's academic progress and provide necessary support.

<br><br>

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### CognifyEdu is built using the following technologies:

- This project uses the [React.js](https://reactjs.org/) framework along with [Redux](https://redux.js.org/) for building the user interface and managing global state.
- For the backend, the project uses the [Laravel](https://laravel.com/) PHP framework, which provides a robust structure for API management, authentication, and database interactions.
- The platform stores data in a [MySQL](https://www.mysql.com/) database, which is ideal for managing relational data such as student profiles, assignments, and grades.
- To provide AI-driven cognitive and behavioral insights, the platform integrates with the [OpenAI API](https://openai.com/) for advanced data processing.
- The platform is deployed and hosted on [AWS](https://aws.amazon.com/) for scalable and secure cloud infrastructure.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> We designed CognifyEdu using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project [Figma](https://www.figma.com/design/U2P8bXvDJkAEcWznBTxUUh/UI-UX-Assignments?node-id=257-428&t=CbqzlIepZUG9RqWT-1) design

### Mockups

| Courses screen                                 | Analysis Screen                                  | Edit Profile Screen                                     |
| ---------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------- |
| ![Courses](./readme/assets/mockup-courses.png) | ![Analysis](./readme/assets/mockup-analysis.png) | ![Edit Profile](./readme/assets/mockup-editprofile.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies:

![ERDiagram](./readme/assets/db-schema.png)

<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

### User Screens

| Landing Screen                           | Login Popup                               |
| ---------------------------------------- | ----------------------------------------- |
| ![Landing](./readme/assets/landing.gif)  | ![fsdaf](./readme/assets/login.gif)       |
| Courses Screen                           | Course Screen                             |
| ![Landing](./readme/assets/courses.gif)  | ![fsdaf](./readme/assets/course.gif)      |
| Analysis Screen                          | Add Insight                               |
| ![Landing](./readme/assets/analysis.gif) | ![fsdaf](./readme/assets/add-insight.gif) |

### Admin Screens

| Users Screen                                | Courses Screen                              |
| ------------------------------------------- | ------------------------------------------- |
| ![Landing](./readme/assets/admin-users.png) | ![fsdaf](./readme/assets/admin-courses.png) |

<br><br>

<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

### Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize interactions with the OpenAI API. By carefully crafting the input prompts, we tailor the cognitive and behavioral assessments to deliver precise insights that enhance the academic development of students.

<img src="./readme/assets/prompt.png"/>

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

### Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to create a robust and scalable backend for the CognifyEdu platform. By harnessing the power of AWS services, we ensure that our AI-driven educational insights are delivered efficiently to support a wide range of users.

<img src="./readme/assets/api-call.png"/>

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

### Precision in Development: Harnessing the Power of Unit Testing:

- This project employs comprehensive unit testing methodologies to ensure the accuracy and reliability of all components in CognifyEdu. By systematically testing individual parts of the platform, we maintain a strong foundation, quickly identifying and addressing issues to provide a stable learning experience.

<img src="./readme/assets/unit-test.png"/>

<br><br>

<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up CognifyEdu locally, follow these steps:

### Prerequisites

Make sure you have the following installed:

- npm
  ```sh
  npm install npm@latest -g
  ```
- Composer
  ```sh
  composer install
  ```

### Installation

Follow these steps to install and set up CognifyEdu locally:

1. Get an API Key at [OpenAI](https://beta.openai.com/signup/)

2. Clone the repo

   ```sh
   git clone https://github.com/MohamadSharafeddine/cognifyedu.git
   ```

3. Navigate to the backend directory and install Composer packages

   ```sh
   cd backend
   composer install
   ```

4. Add your API key to the .env file
   ```env
   OPENAI_API_KEY="ENTER YOUR OPENAI API KEY"
   ```
5. Run database migrations to set up the tables
   ```sh
   php artisan migrate
   ```
6. Start the Laravel development server
   ```sh
   php artisan serve
   ```
   
7. Navigate to the frontend directory and install NPM packages

   ```sh
   cd ../frontend
   npm install
   ```

8. Start the frontend development server
   ```sh
   npm start
   ```

Now, you should be able to run CognifyEdu locally and explore its features.