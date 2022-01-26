# sample-access-management
This repository is to explore the levels of privileges that can be assigned to every member of the organization based on the business requirements.

## Following are the criteria established in this repository.

### 1) Private repository
### 2) 5 Users - Admin, Bravo, Charlie, Delta, Echo
### 3) Branches - Alpha, Beta, Gamma, Master(main)

-> **Admin** has overall access and privileges to all parts of the repository.

-> **Bravo** - All privileges on **Alpha**, and **Master**(main) branches only. No access on other branches.

-> **Charlie** - All privileges on **Master**(main) only. No access on other branches.

-> **Delta** - Only `Pull` and `Clone` privileges on all branches.

-> **Echo** - Not yet defined.

## All users can work in the branches, create pull requests accessible to them.

## **Admin** should approve the `Pull` request by verifying _merge changes_.
