### starter_code 
**Lab DA-1:** Implement a Remote Procedure Call (RPC) framework using Python.
Extend your Python RPC framework to support the remote invocation of: float calculate_grade_average(StudentProfile profile)

The StudentProfile object must contain:
- name (string)
- id (int)
- grades (list of integers)

2. You must submit a Pull Request answering the question:
Implement a validate_types() function within your marshalling layer. This function must check the incoming data on the server side and raise a TypeError if a student attempts to send a string where an int is expected.
- A PR containing a results.md file.

How to Submit:-
Create a Branch: git checkout -b rpc-marshalling-objects

Commit Changes: git commit -m "Brief description of work"

Push to GitHub: git push origin rpc-marshalling-objects

Open a PR: Go to GitHub and click "New Pull Request". Target your main branch.

Tag the Instructor: Mention @manoov in the PR comment.
