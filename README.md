🚀 *TeamSync AI* – Smart Task Maneger

📌 About the Project

# TeamSync AI is an AI-powered, full-stack project and task management platform designed to simplify teamwork and improve productivity. It provides a centralized workspace where teams can create projects, assign tasks, manage deadlines, track progress, and collaborate in real time.

The platform combines traditional project management features with AI-powered assistance to reduce manual planning and make team coordination more efficient. Its AI assistant helps generate task breakdowns and summarizes project progress, allowing users to plan and manage their work more effectively.

TeamSync AI is designed especially for student project teams, college clubs, and small development teams that need an organized and collaborative environment.

✨ Key Features

- User Authentication: Secure registration and login with JWT-based authentication.
- Role-Based Access Control (RBAC): Manage workspace members and control access based on user roles.
- Project Management: Create, organize, and manage multiple projects within a workspace.
- Task Management: Create, assign, update, and track tasks with priorities and deadlines.
- Kanban Board: Visualize task progress through To Do, In Progress, In Review, and Done stages.
- Task Dependencies: Identify blocked tasks and manage prerequisite relationships.
- Real-Time Collaboration: Receive instant updates using Socket.IO without refreshing the page.
- Notifications & Reminders: Get notified about task updates and approaching or missed deadlines.
- AI-Powered Task Planning: Generate suggested tasks and subtasks from natural-language project descriptions.
- AI Progress Summaries: Generate concise project progress reports using task and activity data.
- Analytics Dashboard: Monitor project progress, overdue tasks, workload distribution, and team activity.
- Activity Logs: Maintain a record of important project and task-related actions.

🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend development and user interface |
| Node.js | Backend runtime environment |
| Express.js | REST API development |
| MongoDB | Database management |
| JWT | User authentication |
| Socket.IO | Real-time communication |
| LLM API | AI-powered task generation and progress summaries |
| Git & GitHub | Version control and collaboration |
| Postman | API testing |


## 📂 Project Folder Structure

```text
TeamSync-AI/
│
├── frontend/
│   ├── public/
│   │   └── assets/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Sidebar.jsx
│   │   │   ├── TaskCard.jsx
│   │   │   └── KanbanBoard.jsx
│   │   ├── pages/
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   ├── Projects.jsx
│   │   │   └── Tasks.jsx
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── services/
│   │   │   └── api.js
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── .env
│
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── projectController.js
│   │   ├── taskController.js
│   │   └── aiController.js
│   ├── models/
│   │   ├── User.js
│   │   ├── Workspace.js
│   │   ├── Project.js
│   │   ├── Task.js
│   │   ├── Comment.js
│   │   └── Notification.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── projectRoutes.js
│   │   ├── taskRoutes.js
│   │   └── aiRoutes.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   └── roleMiddleware.js
│   ├── services/
│   │   ├── aiService.js
│   │   └── notificationService.js
│   ├── socket/
│   │   └── socket.js
│   ├── jobs/
│   │   └── reminderJob.js
│   ├── utils/
│   │   └── generateToken.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── .gitignore
├── README.md
└── package.json
```



⚙️ How It Works

1. Users register or log in to the platform.
2. A workspace owner creates a workspace and invites team members.
3. Project leads create projects and assign appropriate roles.
4. Tasks can be created manually or generated with AI assistance.
5. Team members receive assigned tasks with priorities and deadlines.
6. Members update task statuses through the Kanban board.
7. Socket.IO broadcasts authorized updates to connected team members.
8. Scheduled jobs generate deadline reminders.
9. The dashboard displays project progress, workload, and activity.
10. The AI assistant generates task suggestions and progress summaries for user review.

🤖 AI Integration

TeamSync AI integrates an LLM API to make project planning and progress tracking more efficient.

- AI Task Generation: Converts project descriptions into structured task and subtask suggestions.
- AI Progress Summarization: Generates summaries based on task statuses, overdue work, blocked tasks, and recent project activities.
- Human Approval: AI-generated suggestions remain editable drafts. Users can review, modify, approve, or reject them before saving.

🔐 Security

- JWT-based authentication.
- Password hashing for secure credential storage.
- Role-based access control.
- Backend validation of user permissions and project membership.
- Input validation and sanitization.
- Secure handling of API keys and sensitive information.

🎯 Project Objectives

- Simplify project and task management.
- Improve team communication and collaboration.
- Reduce manual follow-ups and missed deadlines.
- Provide better visibility into project progress.
- Use AI to assist with project planning and reporting.

🔮 Future Enhancements

- Email notifications and calendar integration.
- Advanced project analytics and reporting.
- Recurring tasks and customizable workflows.
- Multilingual AI assistance.
- Native mobile application.
- Integration with external productivity tools.

TeamSync AI aims to bring project planning, task management, real-time collaboration, and AI-powered assistance together in one unified platform.
