# hw-proposal

The team lead's repo for this assignment will become the project repo for the team.
For this assignment, submit the link for the project lead's repo in Canvas.
An instructor will add project partners to the team lead's repo after the proposal deadline.
The proposal itself should appear in the [./proposal](proposal) subdirectory, 
where you'll find the [proposal-guidelines.md](proposal/proposal-guidelines.md) 

# Team

**Team members:** Li Shenyu (team leader), Qin Letian (team member)

**GitHub Classroom Repo:** [GitHub Classroom link][(https://github.com/nuwebdev/hw05-proposal-lishenyu1024/)](URL) – Hosted by Shenyu Li

## Project Objectives

Develop a Pet Tinder website that allows pet owners to create profiles for their pets, including adding photos and liking other pets' profiles. The website will also incorporate a Maps API, allowing local pet owners to list their pets for public activities such as group walks, thereby promoting social interaction between pets and their owners.

## User Stories

### Pet Owner
- As a pet owner, I can:
  - Create a profile for my pet
  - Add photos
  - Find other pets nearby to socialize with

### Community Member
- As a community member, I would like to:
  - Explore pets in my area
  - Organize or join group walks

## User Interface Design

The user interface will be simple and engaging, focusing on ease of use. We will use Figma to design the interface, including:

![image](https://github.com/nuwebdev/hw05-proposal-lishenyu1024/assets/156556647/8a9a801a-5336-4575-bd94-4ae1f008a105)


- A landing page with a clear call-to-action (e.g., "Join Now")
![image](https://github.com/nuwebdev/hw05-proposal-lishenyu1024/assets/156556647/264e356b-2f8b-4239-81c2-917891754824)

- Pet's profile creation page including name, age, breed, and photo upload fields
- Main feed showing pet profiles with similar buttons and connection options
  ![image](https://github.com/nuwebdev/hw05-proposal-lishenyu1024/assets/156556647/3d3bf7ed-9a27-4a52-95ca-913832b97706)

- Map interface for viewing and joining local pet events
![image](https://github.com/nuwebdev/hw05-proposal-lishenyu1024/assets/156556647/4227c3c2-d0fe-4627-8304-265f963375b3)

## Architecture and Technical Requirements

### Backend
- **Language and Framework:** Python & Django
  - Utilize Django's back-end logic and database interaction capabilities.
  - Django ORM interacts with MySQL database to manage user and pet information.

### Frontend
- **Framework:** Angular
  - Creating user interfaces using Angular's two-way data binding and modular development methods.

### Database
- **Type:** MySQL
  - Use MySQL database to store user and pet data, including activity information.

## Other Technologies

- Authentication and security: JWT (JSON Web Tokens)
- Front-end and back-end communication: REST API design pattern, using Django REST framework
- Map API integration: Google Maps API or OpenStreetMap API

## Other Requirements

- Acknowledgments: Cite all sources used for development.
- Reproducibility: Provide detailed instructions for setting up the development environment and running the application in the README.md.
- Deployment: Initially set up against a local development server, with a comprehensive privacy policy if deployed publicly.

## Project Management

- **Work Plan:** Detail roles, responsibilities, milestones, and timelines in a separate Markdown file in the proposal subdirectory.
- **Milestones:** Includes initial setup, feature development phases (authentication, profile management, map integration), testing, and final deployment.

### Roles and Responsibilities

- **Shenyu Li:** Project management, front-end development, UI design, and map API integration.
- **Letian Qin:** Back-end development, database management.

