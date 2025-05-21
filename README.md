1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed: These tests would be automatically run when prs are made before merging. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, that is something that is meant to be tested by a unit test.

3) What is the difference between navigation and snapshot mode?

The difference between the two is in the way they analyze a page.

Navigation mode analyzes a page right after it loads and provides an overall performance metric, but can't analyze interactions or changes in content.

Snapshot mode analyzes a page in its current state and is used for finding accessibility issues. However, it can't analyze JS performance or changes to the DOM tree.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
1. It should should have a \[lang\] attribute (accessibility).
2. It should have a `<meta name="viewport">` tag.
3. It should have a meta description.