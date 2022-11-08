# Awesome testRigor [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

testRigor is no-code end-to-end functional testing tool for web, desktop, and mobile testing. 

When it comes to E2E testing, you may want to use a powerful [testRigor](https://testrigor.com/) automation solution. You can create tests covering an entire flow, including 2FA-based logins, email testing validation and manipulation, etc. - in a single test. You can also run these tests on web and mobile browsers with just a config change.

In testRigor you write a specification of how your application is supposed to work instead of code. For example, changing a button to an a-tag won't break the test. A test can look like this:

```
login
check that URL ends with "/home"
```

You can seamlessly work with forms and tables by simulating how a user would express the steps. Therefore it would, for instance, associate labels with inputs so that you can always refer to input by some visible text like a label (or text that looks like a label) or a placeholder. For the tables, it helps even more by enabling things such as:

```
check that table at the row containing stored value "myId" and column "Status" contains "Paid"
```

testRigor also supports visual testing out of the box, no additional configuration is necessary. You can compare any screen to a previous version (ex: post-release verification), save screenshots in test data as the point of comparison, compare individual elements on the screen etc.

```
compare screenshot to previous version
```
or

```
click by image from stored value "logo" with less than "10" % discrepancy
```

Full documentation is available [here](https://testrigor.com/docs/language/) for your convenince. As you can see, it is very declarative and utterly abstracted from the application's code. It might be handy in case you need to approve how things work with a customer, or involve other people to build tests for your application.

> Full documentation for [testRigor](https://testrigor.com/docs/language/)

# Become a testRigor pro
- [What size company is testRigor best suited for?](https://testrigor.com/blog/faq-what-size-company-is-testrigor-suited-best-for/)
- [What if we don’t have dedicated testers, who can write automated tests with testRigor?](https://testrigor.com/blog/faq-what-if-we-dont-have-dedicated-testers-who-can-write-automated-tests-with-testrigor/)
- [How does testRigor use AI?](https://testrigor.com/blog/faq-how-does-testrigor-use-ai/)
- [Does testRigor support Accessibility testing?](https://testrigor.com/blog/faq-does-testrigor-support-accessibility-testing/)
- [Does testRigor have an integration with Jira?](https://testrigor.com/blog/faq-does-testrigor-have-integration-with-jira/)
- [Does testRigor have integration with TestRail?](https://testrigor.com/blog/faq-does-testrigor-have-integration-with-testrail/)
- [How does testRigor's CI/CD integration work?](https://testrigor.com/blog/faq-how-does-testrigors-ci-cd-integration-work/)
- [How do I maintain tests in testRigor?](https://testrigor.com/blog/faq-how-do-i-maintain-tests-in-testrigor/)
- [How does testRigor keep tests stable when I push a new UI change?](https://testrigor.com/blog/faq-how-does-testrigor-keep-tests-stable-when-i-push-a-new-ui-change/)
- [What are testRigor’s End-To-End Tests Actually Testing For?](https://testrigor.com/blog/faq-what-are-testrigors-end-to-end-tests-actually-testing-for/)
- [How is testRigor different from Selenium?](https://testrigor.com/blog/faq-how-is-testrigor-different-from-selenium/)
- [What problem does testRigor solve for its customers?](https://testrigor.com/blog/faq-what-problem-does-testrigor-solve-for-its-customers/)

# Tutorials
- [How to refer to elements](https://testrigor.com/blog/tips-tricks-how-to-refer-to-elements-in-testrigor/)
- [How to achieve more test coverage](https://testrigor.com/blog/how-to-achieve-more-test-coverage-with-no-code-2-0/)

# Blogs
- [How to start with test automation right now](https://testrigor.com/blog/how-to-start-with-test-automation-right-now/)
- [How to automate closed shadow DOM](https://testrigor.com/blog/how-to-automate-closed-shadow-dom-with-testrigor/)
- [How to automate testing tables](https://testrigor.com/blog/how-to-automate-testing-tables/)
- [How to generate, manage and use test data to achieve the best results](https://testrigor.com/blog/how-to-generate-manage-and-use-test-data-to-achieve-the-best-results/)

