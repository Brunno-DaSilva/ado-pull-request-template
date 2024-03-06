# Pull Request Template for ADO repositories

The pull request (PR) process is a critical part of collaborative software development. To ensure that your PR is properly reviewed and integrated into the codebase, it's important to follow a few key steps

## **1. Before Submit a PR** 📢

Before submitting your pull request, make sure that your code is easy to review, maintainable, and readable. The following guidelines will help you to ensure the quality of your code and identify any areas that may require attention.

- **Assume responsibility for the entire file you are modifying**: 
  - Whether you are making a small change to a single line of code or working on a larger feature, it's important to take ownership of the entire file you're working on. This means scanning the file for any low-hanging fruit, such as unused variables, imports, and methods, and fixing them to ensure that the file is clean and organized. 
  - By taking this approach, you can help ensure that your changes are integrated smoothly into the codebase and that the overall quality of the code is maintained.

- **Unused code**: 
  - Any unused code, such as unused imports, unassigned variables, or unused methods, can clutter the codebase and make it harder to read and understand. 
  - Remove any unused code to keep the codebase clean and organized.

- **Duplication**: 
  - Look for duplicate code blocks in your codebase. Duplication can make code harder to maintain, as changes need to be made in multiple places. Refactor duplicate code into reusable functions or modules.

- **Long methods**: 
  - Long methods can be difficult to read and understand. Break down long methods into smaller, more focused functions that do one thing well.

- **Large classes**: 
  - Large classes can be a sign of a lack of cohesion or a violation of the single responsibility principle. 
  - Split large classes into smaller, more focused classes that have a clear purpose.

- **Nested conditionals**: 
  - Deeply nested conditional statements can be hard to follow and can make code more error-prone. 
  - Simplify nested conditionals by using early returns, guard clauses, or switch statements.

- **Magic numbers and strings**: 
  - Magic numbers and strings are hard-coded values that have no clear meaning. 
  - Use constants or enums to give meaning to these values and make the code more readable.

- **Comments**: 
  - Extensive comments can be a sign of unclear code. 
  - Try to write code that is self-documenting and does not require comments to explain its purpose.

- **Code formatting**: 
  - Consistent formatting makes code easier to read and understand. 
  - Use a linter to ensure that your code follows a consistent style and formatting.

<br />

## **2. PRs House Rules** 🏠

- **Review the PR with another developer** :
  - Use the daily developer work session to review the PR with another developer or schedule a meeting separately.
  - This will greatly reduce the back-and-forth churn that elongates the PR review and approval process (CHANGE to the current process).

- **Set up a meeting with QA**: 
  - It is important to collaborate with the QA analysts to review the issue at hand. Maintaining good communication with them will help ensure that they have all the necessary information to accurately test your code.

- **If your PR is blocked for any reason**:  
  - Update the status to blocked.  
  - Add notes indicating why is it blocked and who can get you the answer.  Please tag them.
  - Add a comment to the User Story or Bug
  - Bring it up in daily standups

<br />

- **Additional Overall rules**: 
  - If you create the PR, you own it and see it through approval. (No change from status quo)

  - Outstanding PR’s need to be called out by you in daily standup. (No change from status quo)

  - If your PR is aging, reach out to your team to get it reviewed. (No change from status quo)

  - PM will be following blocked work items daily. They will be pushing to understand why it is blocked and following up to get the answers that are needed. Expect to be pestered relentlessly if you are blocking progress.

  - Before submitting a PR ensure that all packages and dependencies are properly updated or generated and the team is informed.
    - Especially if your code relies on internal dependencies version.  

<br />

<div style="border-left: 2px solid #5bc0de; background:#e3edf2; padding: 0.8rem;" >
<span >
💡 <b>Attention</b>: If a PR is greater than 1 day old with no action, this needs to be escalated to the Development Manager. 
</span>
</div>

<br />


<br>

##3. PR Template:🚧

<br />

<details style="padding-left: 50px; color: darkBlue">
<summary>How it's look like</summary>

  
### Description: 

	A small paragraph description

### Has QA tested this feature?
- [ ] Yes
- [ ] No


### Where should the reviewer start?

	At lamp5\lamp5-audit\src\engines\DuplicateRows.Engine.ts

### Does this add new dependencies or tech debt? Is there an installation procedure? (yarn, npm, NuGet, etc.)
- [ ] Yes
- [ ] No

### Does this work have unit and/or component tests?
- [ ] Yes
- [ ] Not Yet
- [ ] No

### How should this be manually tested?

	By uploading an audit file with duplicate entries and running lamp5-audit locally

### Any background context you want to provide?

	Acceptance criteria have been met, duplicate items should be displayed as expected

### Screencap (Gif or image):

	See screenshots of the expected result below:

</details>

<br/>


<details style="padding-left: 50px; color: dark-blue">
<summary>Click to see the template markdown code</summary>

```

### Description: 

	A small paragraph description

### Has QA tested this feature?
- [ ] Yes
- [ ] No


### Where should the reviewer start?

	At lamp5\lamp5-audit\src\engines\DuplicateRows.Engine.ts

### Does this add new dependencies or tech debt? Is there an installation procedure? (yarn, npm, NuGet, etc.)
- [ ] Yes
- [ ] No

### Does this work have unit and/or component tests?
- [ ] Yes
- [ ] Not Yet
- [ ] No

### How should this be manually tested?

	By uploading an audit file with duplicate entries and running lamp5-audit locally

### Any background context you want to provide?

	Acceptance criteria have been met, duplicate items should be displayed as expected

### Screencap (Gif or image):

	See screenshots of the expected result below:


```
</details>

<br />

<br/>

<a style="background: #24b1e6; color: #fff; padding: 0.6rem; text-decoration:none;" href="#">Back to top ↑ </a>

<br/>

---








