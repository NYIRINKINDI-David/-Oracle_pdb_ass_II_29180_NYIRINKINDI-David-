
# Oracle PDB Assignment II — NYIRINKINDI DAVID — 29180

## Overview of Tasks

This repository documents the completion of Oracle PDB Assignment II, covering four tasks:
1. Creating a new Pluggable Database (PDB) with a dedicated user
2. Creating and deleting a temporary PDB
3. Verifying access via Oracle Enterprise Manager (OEM)
4. Documentation and reporting (this README)

All tasks were completed individually in my own Oracle environment.

## Oracle Environment Used

<!-- Replace with what you actually used, e.g.:
Oracle Database 19c Enterprise Edition, running on [Oracle Linux 8 / VirtualBox VM / Oracle Cloud instance / other].
Connected via SQL*Plus / SQLcl and Oracle Enterprise Manager Express.
-->
_Describe your Oracle setup here._

## Task Explanations

### Task 1: Create a New Pluggable Database

- **PDB created:** `da_pdb_29180`
- **User created inside PDB:** `david_plsqlauca_29180`

Steps taken:
1. Connected to the container database as SYSDBA.
2. Created the PDB `da_pdb_29180` from the seed database.
3. Opened the PDB and saved its state.
4. Created the user `david_plsqlauca_29180` inside the PDB and granted session/resource privileges.
5. Verified the user was created successfully.

**Screenshots:**

| PDB Creation | PDB Open State | User Created |
|---|---|---|
| ![PDB creation](screenshots/pdb_creation/pdb_creation_command.png) | ![PDB open state](screenshots/pdb_creation/pdb_open_state.png) | ![User created](screenshots/pdb_creation/user_created.png) |

### Task 2: Create and Delete a PDB

- **Temporary PDB:** `da_to_delete_pdb_29180`

Steps taken:
1. Created the temporary PDB `da_to_delete_pdb_29180`.
2. Opened it and confirmed it existed via `SHOW PDBS`.
3. Closed the PDB (`CLOSE IMMEDIATE`).
4. Dropped the PDB including its datafiles.
5. Confirmed it no longer exists.

**Screenshots:**

| PDB Creation + Result | PDB Deletion + Result |
|---|---|
| ![PDB creation](screenshots/pdb_deletion/pdb_creation.png) | ![PDB deletion](screenshots/pdb_deletion/pdb_deletion.png) |

### Task 3: Oracle Enterprise Manager (OEM) Setup

Steps taken:
1. Accessed OEM Express at the environment's HTTPS port.
2. Logged in with a user holding EM Express privileges.
3. Confirmed the dashboard reflects the Oracle environment and the PDB/tasks completed above, with the username visible.

**Screenshot:**

![OEM dashboard](screenshots/oem_dashboard/oem_dashboard.png)

## Challenges Faced

<!-- Replace with anything you actually ran into, e.g. listener port conflicts, file path errors, forgotten passwords, etc. If none, say so. -->
_Describe any issues encountered and how you resolved them, or state that none were encountered._

## Integrity Statement

I confirm that this work was completed individually, using my own execution and Oracle environment, without copying commands, screenshots, or repositories from classmates.

## Submission Details

- **Repository Link:** [GitHub URL here]
- **PDB Name Created:** da_pdb_29180
- **Issues Encountered:** [Yes/No]
