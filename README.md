<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> An AI-driven educational platform that provides cognitive and behavioral insights by integrating academic performance with psychological assessments to enhance student development.
>
> CognifyEdu aims to streamline the learning process by providing a user-friendly platform for managing assignments, tracking student progress, and offering insightful cognitive and behavioral data. We believe in enhancing the educational experience by empowering teachers, students, and parents with meaningful insights to foster student growth and development.

### User Stories

- As a teacher, I want to view detailed student profiles, so I can provide targeted support and interventions.
- As a student, I want to receive personalized learning paths, so I can focus on my strengths and areas for improvement.
- As a parent, I want to understand my child’s abilities and development, so I can support their learning at home effectively.

<br><br>

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### CognifyEdu is built using the following technologies:

- This project uses the [React.js](https://reactjs.org/) framework for building the user interface. React is a JavaScript library for creating dynamic, responsive web applications.
- For the backend, the project uses the [Laravel](https://laravel.com/) PHP framework, which provides a robust structure for API management, authentication, and database interactions.
- The platform stores data in a [MySQL] (https://www.mysql.com/) database, which is ideal for managing relational data such as student profiles, assignments, and grades.
- To provide AI-driven cognitive and behavioral insights, the platform integrates with the [OpenAI API] (https://openai.com/) for advanced data processing.
- The platform is deployed and hosted on [AWS] (https://aws.amazon.com/) for scalable and secure cloud infrastructure.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> We designed CognifyEdu using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/U2P8bXvDJkAEcWznBTxUUh/UI-UX-Assignments?node-id=257-428&t=CbqzlIepZUG9RqWT-1)

### Mockups

| Home screen                               | Menu Screen                             | Order Screen                            |
| ----------------------------------------- | --------------------------------------- | --------------------------------------- |
| ![Landing](./readme/assets/1440x1024.png) | ![fsdaf](./readme/assets/1440x1024.png) | ![fsdaf](./readme/assets/1440x1024.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies:

![ERDiagram](./readme/assets/CognifyEdu_ERDiagram.png)

<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

### User Screens

| Landing Screen                            | Login Popup                             |
| ----------------------------------------- | --------------------------------------- |
| ![Landing](./readme/assets/1440x1024.png) | ![fsdaf](./readme/assets/1440x1024.png) |
| Courses Screen                            | Course Screen                           |
| ![Landing](./readme/assets/1440x1024.png) | ![fsdaf](./readme/assets/1440x1024.png) |
| Analysis Screen                           | Insights Screen                         |
| ![Landing](./readme/assets/1440x1024.png) | ![fsdaf](./readme/assets/1440x1024.png) |

### Admin Screens

| Users Screen                              | Courses Screen                          |
| ----------------------------------------- | --------------------------------------- |
| ![Landing](./readme/assets/1440x1024.png) | ![fsdaf](./readme/assets/1440x1024.png) |
<br><br>

<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

### Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize interactions with the OpenAI API. By carefully crafting the input prompts, we tailor the cognitive and behavioral assessments to deliver precise insights that enhance the academic development of students.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

### Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and scale the CognifyEdu platform. AWS ensures that our AI-driven educational insights are delivered efficiently and securely to support a wide range of users.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

### Precision in Development: Harnessing the Power of Unit Testing:

- This project employs comprehensive unit testing methodologies to ensure the accuracy and reliability of all components in CognifyEdu. By systematically testing individual parts of the platform, we maintain a strong foundation, quickly identifying and addressing issues to provide a stable learning experience.

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
   git clone [github](https://github.com/MohamadSharafeddine/cognifyedu.git)
3. Navigate to the backend directory and install Composer packages
   ```sh
   cd backend
   composer install
   ```
4. Add your API key to the .env file
   ```env
   OPENAI_API_KEY="ENTER YOUR OPENAI API KEY"
   ```
5. Navigate to the frontend directory and install NPM packages
   ```sh
   cd ../frontend
   npm install
   ```
6. Start the development server
   ```sh
   npm start
   ```

Now, you should be able to run CognifyEdu locally and explore its features.
