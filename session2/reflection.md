# Session 2 Reflection



### 1. How do Issues and Pull Requests work together to support change control?



GitHub Issues record the change request, its purpose and acceptance criteria. Pull Requests show the actual changes made to address the Issue and allow them to be reviewed before merging. Linking a Pull Request to an Issue provides traceability from the original request to the completed change.



### 2. Why did the merge conflict in Part 4 happen, and how can a team reduce conflicts?



The merge conflict happened because branch-a and branch-b changed the same line in the same file to different values. Git could not decide which version to keep automatically. A team can reduce conflicts by communicating regularly, pulling the latest changes, keeping branches short-lived and avoiding unnecessary changes to the same files.



### 3. What would be lost if changes were merged directly into main without a Pull Request?



Merging directly into main without a Pull Request would remove the opportunity for team review and feedback before the changes are accepted. It would also reduce the visibility of the changes, reviewer comments and evidence that acceptance criteria were checked. This would make change control and traceability more difficult.

