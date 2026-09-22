
# Oracle PDB Assignment II — NYIRINKINDI DAVID

**Student ID:** 29180  
**Student Name:** NYIRINKINDI DAVID

## Overview

This repository contains the evidence and documentation for the Oracle Pluggable Database (PDB) assignment. The assignment covers:

1. Creating a new Pluggable Database (PDB)
2. Creating and deleting a temporary PDB
3. Using Oracle Enterprise Manager (OEM)
4. Documenting and reporting the completed work

All screenshots included in this repository are provided as evidence of the work performed.

---

## Oracle Environment

- **Student:** NYIRINKINDI DAVID
- **Student ID:** 29180
- **Main PDB Name:** `NY_pdb_29180`
- **Temporary PDB Name:** `NY_to_delete_pdb_29180`
- **Username inside PDB:** `David_plsqlq_29180`
- **Password:** Self-chosen password used during the practical work

> **Security note:** The password is intentionally not published in this repository.

---

# Task 1: Create a New Pluggable Database

## Requirements

The first task required:

- Creating the PDB successfully
- Creating a user inside the PDB
- Using the user account for future class work
- Providing screenshots as evidence

### PDB Details

**PDB Name:**

```text
NY_pdb_29180
```

**User created inside the PDB:**

```text
David_plsqlq_29180
```

### Evidence

Upload the relevant screenshots to:

```text
screenshots/pdb_creation/
```

Add them below using the following format:

```markdown
![PDB creation](screenshots/pdb_creation/pdb_creation.png)
```

### PDB Creation Screenshot

![PDB creation](screenshots/pdb_creation/pdb_creation.png)

### User Created Inside PDB Screenshot

![User created inside PDB](screenshots/pdb_creation/user_created.png)

---

# Task 2: Create and Delete a PDB

## Naming Convention

The temporary PDB follows the required naming format:

```text
NY_to_delete_pdb_29180
```

## Requirements

- Create the temporary PDB successfully
- Verify that the PDB exists
- Delete the PDB completely
- Confirm that the PDB no longer exists

## Evidence

Upload the screenshots to:

```text
screenshots/pdb_deletion/
```

### PDB Creation

The screenshot should show the command used to create the temporary PDB and the resulting output.

![Temporary PDB creation](screenshots/pdb_deletion/pdb_creation.png)

### PDB Deletion

The screenshot should show the command used to delete the temporary PDB and the resulting output.

![Temporary PDB deletion](screenshots/pdb_deletion/pdb_deletion.png)

### Verification

The final verification screenshot should show that the temporary PDB no longer exists.

![PDB deletion verification](screenshots/pdb_deletion/pdb_deleted_verification.png)

---

# Task 3: Oracle Enterprise Manager (OEM)

## Requirements

The OEM task required:

- Accessing Oracle Enterprise Manager
- Showing that the dashboard reflects the Oracle environment
- Showing the completed PDB-related work where applicable
- Making the username visible on the dashboard

## Evidence

Upload the OEM screenshot to:

```text
screenshots/oem_dashboard/
```

### OEM Dashboard

![Oracle Enterprise Manager dashboard](screenshots/oem_dashboard/oem_dashboard.png)

The screenshot should clearly show the relevant Oracle Enterprise Manager dashboard information and the username where required.

---

# Task 4: Documentation & Reporting

This README provides the documentation and evidence structure for the assignment.

The repository is organized as follows:

```text
oracle_pdb_ass_II_29180_NYIRINKINDI/
│
├── README.md
│
└── screenshots/
    ├── pdb_creation/
    │   ├── pdb_creation.png
    │   └── user_created.png
    │
    ├── pdb_deletion/
    │   ├── pdb_creation.png
    │   ├── pdb_deletion.png
    │   └── pdb_deleted_verification.png
    │
    └── oem_dashboard/
        └── oem_dashboard.png
```

Replace the example filenames above with the actual names of your uploaded screenshots if they are different.

---

# Challenges Encountered

Use this section to briefly describe any problems encountered while completing the tasks.

Example:

- Initial connection/setup issues were resolved before creating the PDB.
- PDB status was checked after creation to confirm that it was available.
- The temporary PDB was verified before and after deletion.
- OEM was checked to confirm that the Oracle environment was accessible.

If no significant problems were encountered, write:

```text
No significant issues were encountered during the completion of the assignment.
```

---

# Integrity Statement

I, **NYIRINKINDI DAVID (Student ID: 29180)**, confirm that the work and evidence submitted in this repository represent my own execution and documentation of the assignment.

I have followed the assignment requirements and have not copied commands, screenshots, repositories, or other submission materials from classmates.

---

# Submission Details

```text
Repository Link: [GitHub URL]

PDB Name Created: NY_pdb_29180

Issues Encountered: [Yes/No]
```

If issues were encountered, briefly describe them in the **Challenges Encountered** section above.

---

# Final Checklist

- [ ] GitHub repository is public
- [ ] Repository name follows the required format
- [ ] Correct PDB name used: `NY_pdb_29180`
- [ ] User created inside the PDB
- [ ] Temporary PDB created: `NY_to_delete_pdb_29180`
- [ ] Temporary PDB deleted completely
- [ ] Deletion verified
- [ ] OEM dashboard screenshot included
- [ ] Username visible where required
- [ ] Screenshots are clear and readable
- [ ] README is complete
- [ ] Submission details completed
- [ ] Google Form submitted before the deadline
