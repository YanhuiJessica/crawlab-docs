## Permission Management

Crawlab strengthens the support of permission management from version v0.4.9, which makes the permission management more complex and practical and provides the support of permission management for enterprise users.

### User Role

Crawlab's permission management is a simple version of RBAC. In short, Crawlab has two roles: 'manage users' and 'ordinary users'.

- **manage users**：You can view and operate the data of all users, including spiders, projects, tasks, etc., and see the user management page;
- **ordinary users**：You can only view and operate your own data, not see the user management page.

### Public Spider

You can see the "public or not" options on the spider details-overview page. If it is checked and saved, it means that the spider is a public spider, that is, all users can view it, but other users can't modify the spider except the administrator, they can only copy the spider as their own workspace.