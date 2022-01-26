# sample-access-management
This repository is to explore the levels of privileges that can be assigned to every member of the organization based on the business requirements.

## Following are the criteria established in this repository.

### 1) Private repository
### 2) 5 Users - Admin, Bravo, Charlie, Delta, Echo
### 3) Branches - Alpha, Beta, Gamma, Master

-> **Admin** has overall access and privileges to all parts of the repository.\n
-> **Bravo** - All privileges on **Alpha**, and **Master** branches only. No access on other branches.\n
-> **Charlie** - All privileges on **Master** only. No access on other branches.\n
-> **Delta** - Only `Pull` and `Clone` privileges on all branches.\n
-> **Echo** - Not yet defined.\n

## All users can work in the branches, create pull requests accessible to them.

## **Admin** should approve the `Pull` request by verifying _merge changes_.
