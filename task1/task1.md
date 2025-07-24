## Task-1 : User and Group Administration

- Problem Statement: 

    - Develop a script to automate user and group administration on a RedHat Linux system.

    - Create a shell script to add, delete, and list users and groups.

- Using the provided CSV files (add-user-db.csv, delete-user-db.csv, and delete-group-db.csv), you will automate the process of adding, deleting, and listing users and groups.

    - `add-user-db.csv`: This file contains users and their associated groups that need to be added to the system
        ```bash
        User,Group
        pramin,developers
        bibek,admins
        pragyik,designers
        pranav,devops
        ayush,testers
        primeagen,developers
        oggy,testers
        ```

    - `delete-user-db.csv`: This file lists users that need to be deleted from the system.
        ```bash
        User
        pramin
        bibek
        ```

    - `delete-group-db.csv`: This file lists groups that need to be removed.
        ```bash
        Group
        developers
        testers
        ```
