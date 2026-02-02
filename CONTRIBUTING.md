# Contribute to LMDDI

CTS values and encourages community contributions to our code and documentation. If you want to contribute to LMDDI repositories, please review the following guidance. For documentation-specific information, see the [Contributing to LMDDI documentation](#).

LMDDI is a software stack consisting of a collection of **drivers, development tools, and APIs** that enable systems programming from the low-level kernel to device drivers. Some components are inherited from external projects (such as [LLVM](https://github.com/llvm/llvm-project) and kernel drivers), which follow their own contribution guidelines and workflows. Refer to their repositories for more information. All other LMDDI components follow the workflow described below.

## Development Workflow

LMDDI uses **GitHub** to host code, collaborate, and manage version control. All changes should be submitted via **pull requests (PRs)**. We also use **GitHub issues** to track known bugs and feature requests.

### Issue Tracking

Before filing a new issue, search the [existing issues](#) to ensure it has not already been reported.

**General issue guidelines:**
- Use your best judgment for issue creation. If the issue exists, upvote it and provide additional details, including reproduction steps.
- If unsure whether your issue is the same as an existing one, err on the side of caution and file a new issue, linking the similar one if applicable.
- Provide **as much information as possible**, including logs, script outputs, and configuration details, to help reproduce the issue.
- Check your issue regularly, as maintainers may request further information.

### Pull Requests

PRs should **target the default integration branch** (typically `develop`). Follow this process for creating a PR:

1. Identify the issue you want to fix.  
2. Target the default branch for integration.  
3. Ensure your code builds successfully.  
4. Run the **component test suite** and include the log of successful tests in your PR.  
5. **Do not break existing test cases.**  
6. **New functionality must include new unit tests**:  
   - If adding a feature, provide an application or test to ensure long-term validity.  
7. **Do not copy proprietary code.**  
8. **All code must be legally safe and GPL-compatible**:  
   - Contributions must be original work or properly licensed open-source code that permits redistribution and modification under GPL.  
   - Do not submit proprietary, closed-source, or restricted code.  
   - Third-party code must include proper attribution and comply with its license.  
   - Code written for an employer or third party may only be submitted with **explicit permission** to release under GPL.  
9. Ensure **good test coverage** for all new code.  
10. **Provide environment and hardware details:**  
    - Specify your **distribution, architecture, kernel configuration**, and **the specific hardware your driver targets**.  
11. **Test on the same kernel version as the target branch:**  
    - Drivers must be tested on the same kernel version as the target branch.  
    - Include the **kernel version** in your PR and test logs.  
12. Submit your PR and collaborate with the reviewer or maintainer until it is approved.  
13. Once approved, PRs may be merged into the component during the release cycle as coordinated by the maintainer.  
14. You will be notified once your change is committed.  

> **Important:** By submitting a PR, you agree to license your contribution under the terms of the `LICENSE.txt` file in the corresponding repository. Each LMDDI repository may use a different license. Check the [LMDDI licensing page](#) for details.

### New Feature Development

Propose new features via the **GitHub Discussion forum (Ideas category)**. Maintainers provide guidance and feedback on feature development.

### Documentation

Submit documentation changes to the LMDDI documentation repository. Documentation should reflect any new features, APIs, or modifications.

### Future Development Workflow

The current LMDDI workflow is GitHub-based. If this changes in the future, contribution guidelines, tools, and links will be updated accordingly.
