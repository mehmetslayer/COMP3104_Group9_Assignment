# COMP3104_Group9_Assignment

## Group Members
- **Leader:** Mehmet Emin Onem (101374462) - [GitHub](https://github.com/mehmetslayer)
- **Member 2:** Disha Padsala (101581979) -  [Github](https://github.com/D81979)
- **Member 3:** Maria Tai (101563558) - [Github](https://github.com/mmmtl)
- **Member 4:** Junyong Choi (101539862) - [GitHub](https://github.com/Junyong0619)


## Project Description
This repository hosts the group assignment for COMP3104 DevOps course, focusing on collaborative Git workflows, branching strategies, and CI/CD integration.

## Setup Instructions
1. Clone the repository.
2. Switch to your branch using `git checkout STUDENTID-Name`.
3. Add or edit only your own three files (`STUDENTID_gb.txt`, `STUDENTID_devops.txt`, `STUDENTID_sdlc.txt`) in the repository root, then open a Pull Request into `master`.

## CI/CD Pipeline
The project utilizes GitHub Actions for continuous integration. The workflow is defined in `.github/workflows/ci.yml`. It runs on every push and pull request to `master` (and can be started manually from the Actions tab), checks out the repository on an `ubuntu-latest` runner and runs a simple script, so every merge is verified by a green pipeline before it lands.

## Branching Strategy
Each member has their own branch named `STUDENTID-Name`. All changes are merged into the `master` branch via Pull Requests.
