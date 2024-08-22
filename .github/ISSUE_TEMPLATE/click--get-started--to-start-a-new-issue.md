---
name: Click "Get started" to start a new issue
about: Please use this issue template instead of creating a blank issue
title: ''
labels: ''
assignees: ''

---

GitHub issues can be used to ask the Product team a question about a specific issue or to get input/advice on Product related items. If you _THINK_ that you may have found a bug but are not sure if it is truly a bug, you can post your question here. In addition, if you need advice on best practice to approach a complex situation, you can post the need/question here.

**Please consider the following key points before entering a GitHub Issue:**
* Refer to existing [documentation](https://docs.guidewire.com/cloudProducts/).
* Reproduce the issue in local by following real life scenarios such as running daily/monthly cycles without skipping steps etc.
* Reach out to your POD architect to validate questions or findings.
* Is it already a GitHub issue (open/closed)?
* Is it already an INCICE or INC ticket?
* Reproduce the same issue in [IIC Model](https://iic-model.in-dev.inpd.guidewire.net/) in a similar way as described earlier.
* Has it already been fixed in later versions than the version the customer is currently on?

For more information on Github issues, see this confluence page: https://guidewireconfluence.atlassian.net/wiki/x/SB4OC

***Please remove the above advice and fill in the information below before submitting your issue***
-----

**Describe the problem or question**
A clear and concise description of what the problem or question is.
Always include the name of the customer, planet/environment and version of the core.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. See error ...

**Expected behavior**
A clear and concise description of what you expected to happen. If the issue regards performance, provide absolute and objective performance expectations.

**Screenshots, full error message and stack trace, and objective information**
- If applicable, add screenshots to help explain your problem.
- Include the full text of any error message visible to the user or found in logs (even if it is already in a screen shot). If found in logs, include the full stack trace as well as a link to the error log in Datadog. Don't forget that Datadog logs and other info are only easily available for a week or two. So always include an additional screenshot of any interesting Datadog logs you provide links for so the reader doesn't have to figure out how to rehydrate the logs (if they even can) to see what you're seeing.
- Use [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to format the details and make them readable.
- For performance-related issues, provide absolute and objective measurements of performance. They can be "rough" but they cannot be subjective (e.g. "too slow").
- For memory-related issues, provide a clear summary of what you found the heap was fully of after analyzing a heap dump produced from an OutOfMemoryError or similar.
- Do not attach a separate PDF, Word doc or Google doc with the above information. Include it directly in the issue. This makes it searchable. If a customer sent a document, copy and format its key contents here and include it as an attachment. _Do not just include it as an attachment._

**Additional context**
Add any other context or information about the problem or question here. Add attachments that provide more details or are needed to reproduce the problem, but not as a substitute for the above.
