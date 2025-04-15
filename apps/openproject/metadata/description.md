# OpenProject

OpenProject is a free and open source project management software.

## Features

- **Project Planning and Scheduling**: Create and schedule projects, define work packages and track time
- **Task Management**: Create tasks, assign them to users, and track progress
- **Team Collaboration**: Coordinate with team members through discussions, comments, and notifications
- **Agile & Scrum**: Manage sprints, backlogs, and tasks with agile methodologies
- **Gantt Charts**: Visualize project timelines, dependencies, and milestones
- **Time and Cost Reporting**: Track time spent on tasks and generate cost reports
- **Document Management**: Store project-related documents and files
- **Wiki**: Create and maintain project documentation

## First Login

After installation, you can access OpenProject at the designated URL. Default login credentials are:

- Username: `admin`
- Password: `admin`

For security reasons, please change these credentials after your first login.

## Documentation

For more detailed information about OpenProject features and functionality, please refer to [the official OpenProject documentation](https://www.openproject.org/docs/).

## Troubleshooting

### HTTPS/SSL

By default, OpenProject starts with the HTTPS option enabled, but it does not handle SSL termination itself. This is why the installer sets OPENPROJECT_HTTPS=false by default. If you're running behind a TLS-terminated proxy and want to enable HTTPS mode, you can change this setting.

### Connection Issues

If you're experiencing network issues or timeouts, it might be related to DNS resolution. Make sure your container has proper DNS resolution to access external services.

## Source Code

OpenProject is open source software. You can find the source code on [GitHub](https://github.com/opf/openproject).