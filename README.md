# Jira Cloud Plugin: Manage Releases

## Overview
This Jira Cloud plugin introduces a new project-level permission called "Manage Version". Users with this permission can create and edit Jira Versions/Releases without requiring full Jira Project Administrator rights. This allows for more flexible versions/Releases management by project contributors, while maintaining overall project security and control.

## Features
### New Project Permission: "Manage Version"
The plugin adds a dedicated permission to the project's permission scheme, called "Manage Version". Users assigned this permission can manage project versions, including creating and editing versions, without needing to be a Project Administrator.

<img width="1097" alt="Screenshot 2024-09-03 at 9 29 36 AM" src="https://github.com/user-attachments/assets/615e1bc5-3c30-4389-83ce-644a08ae67df">

### View Project Versions/Releases
Users can view a list of all project-specific Versions/Releases in the project’s **Manage Releases** section. Each version is displayed along with key details such as the name, start date, release date, and status.

**Version Details:** Clicking on a version’s name opens a detailed page, where users can view more details about the version's properties.

<img width="1097" alt="Screenshot 2024-09-05 at 6 46 47 AM" src="https://github.com/user-attachments/assets/ac30e662-ec00-45f3-a5ed-caeff08704bd">


### Filter Versions/Releases
A search and filter functionality is provided to help users quickly find specific versions. Versions can be filtered based on name, and status to make it easier to manage large lists of versions. The plugin also supports sorting on table columns in the version list view. Users can sort by any of the available columns such as version name, start date, or release date. Sorting can be done in ascending or descending order by clicking the column headers.

<img width="1097" alt="image" src="https://github.com/user-attachments/assets/8dcc6990-6067-44d0-9390-5fb4a3407002">


### Create or Edit Versions/Releases
Users with the "Manage Version" permission can:
**Create New Versions:** Define new versions by specifying the version name, start date, release date, and optional description.
**Edit Existing Versions:** Modify details of an existing version, such as changing the name, updating dates, or changing the status.

<img width="627" alt="image" src="https://github.com/user-attachments/assets/fd53ed0a-ccdc-4059-83ed-baec5757efd1">

<img width="627" alt="image" src="https://github.com/user-attachments/assets/6df8c3c9-af46-47f0-9d2e-f9d5c25b5fc8">


### Validation Errors
To ensure data accuracy and consistency, validations are enforced:
**Name:** A unique name is required for each version.
**Start Date:** Cannot be later than the release date.
**Release Date:** Must be a valid date, and if specified, cannot precede the start date.

<img width="576" alt="image" src="https://github.com/user-attachments/assets/37761620-ef6d-4abc-9207-37e8f651ede1">
< br/>

<img width="576" alt="image" src="https://github.com/user-attachments/assets/4e0edcb5-5a1f-4e62-9641-4d924cd50536">
< br/>

<img width="576" alt="image" src="https://github.com/user-attachments/assets/aa954942-013b-45e1-9ef4-9cbaafaa9f58">


## Limitation
**Delete Version:** Users with the "Manage Version" permission cannot delete versions. Only users with full Project Administrator rights are allowed to delete versions. This ensures that version deletions, which are often more critical and irreversible, remain in the hands of trusted administrators.

### Example Use Case
In scenarios where multiple teams are working on the same project, such as with Jira Align programs mapped to a single project, there are often multiple Scrum Masters or Product Owners who need to manage versions. Instead of granting Project Administrator rights to all these users, you can assign them the "Manage Version" permission. This approach allows them to create and edit versions as needed without giving them full control over project settings. This helps maintain security while enabling collaborative version management across teams.

## Usage
Assigning the Permission: Administrators can assign the "Manage Version" permission to specific users or groups through the project’s permission scheme.
Managing Versions: Users with the "Manage Version" permission can navigate to the version management section of a Jira project and perform version-related actions, including filtering, creating, and editing versions.

## Conclusion
This plugin enables more efficient and flexible version management in Jira projects by delegating version control responsibilities to non-administrators. The "Manage Version" permission allows teams to better control and update project versions without needing full project administrative rights, while ensuring that only project administrators can perform sensitive actions like deleting versions.

# Jira Cloud Plugin: Privacy Policy

## Introduction

This Privacy Policy describes how the Manage Releases Plugin (the "App") collects, uses, and shares information about you when you use the App within Atlassian Jira Cloud. By using the App, you agree to the collection and use of information in accordance with this policy.

## Information We Collect

The App may collect the following types of information: User Information: The App may access your Jira user profile, including your username, account ID, and project roles, to manage permissions and functionality within the App. Project Information: The App may access and manage Jira project data, including project keys, version information, and project permissions.

## How We Use Information

The information collected is used solely for the purpose of providing the functionality of the Manage Version Plugin, including: Managing Versions: The App allows users to manage Jira project versions without requiring full Project Administrator rights. Permission Management: The App checks and manages user permissions within Jira to ensure that only authorized users can manage versions.

## Sharing of Information

The Manage Version Plugin does not share your information with any third parties. All data accessed by the App is used exclusively within the Jira Cloud environment and is not transmitted outside of Jira.

## Data Security

We take the security of your data seriously. The App operates within Atlassian's secure cloud environment, and we follow industry best practices to protect your information.

## Your Rights

You have the right to: 

Access: Request access to the information the App collects about you. 

Correction: Request corrections to any information that is inaccurate or incomplete. 

Deletion: Request the deletion of your information if it is no longer necessary for the purposes for which it was collected.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page, and we will notify you of any significant changes by updating the effective date at the top of this policy.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at [support@mj-jugad-apps.atlassian.net].
