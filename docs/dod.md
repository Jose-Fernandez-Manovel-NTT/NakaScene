---
title: "Definition of Done"
metaTitle: "Definition of Done"
metaDescription: "Definition of Done"
---

# Definition of Done

## User story:


- **Code Complete:** The code for the user story must be written, reviewed, and approved by the development team. All code must adhere to the company's coding standards, best practices, and design patterns.
- **Unit Testing:** The code must be thoroughly unit tested, with all tests passing. The tests should cover all functional requirements and edge cases and should be automated where possible.
- **Integration Testing:** The user story must be integrated into the existing system and tested to ensure that it works correctly with all other components. Should be automated where possible.
- **Performance Testing:** The user story must meet all non-functional requirements related to performance, such as response times, load handling, and scalability. Should be automated where possible.
- **Security Review:** The user story must undergo a security review to ensure that it complies with the company's security policies and best practices, and that it does not introduce any new vulnerabilities. Automatic quality tools could check this.
- **Documentation:** All necessary documentation must be completed, including any updates to the system architecture, user guides, and developer documentation. The documentation should be clear, concise, and easily accessible to all relevant stakeholders.
- **Demo:** The completed user story must be demonstrated to the product owner, stakeholders, and other team members to ensure that it meets the acceptance criteria and to gather any feedback.
- **Sign-off:** The product owner must review and sign off on the user story, confirming that it meets all the acceptance criteria and that any feedback has been addressed.
- **Branch:** the feature is merged into the develop/release branch and the tests are in green.
- **Backlog:** the user story is updated in the backlog.


**Before a PR can be merged into dev, the following criteria must be met:**

- The requested functionality/bugfix has been implemented
- Any changes to the database schema must be made in the dacpac
- It works locally tested with Postman, Swagger
- It works in development (requiring any variables added to the pipeline) tested with Postman, Swagger
- Unit tests added
- All comments resolved in the PR
- If needed - local data script updated
- If needed - Postman collection updated
- Once the above criteria has been met and the PR has been merged into the develop branch the task is DONE
