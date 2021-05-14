# The Exercism V3 Beta

We're nearly ready to launch v3 of Exercism, culminating nearly two years of hard work 🎉

We are running a phased beta of the website. 
We'd love your help in highlighting any bugs or issues!
**Please read this document carefully before getting started.**

Also, please note that the purpose of this website is to find things that are broken, so that we can ship this new version of the platform.
**It is not to assertain peoples thoughts or opinions on v3 in general, or to get ideas for improvements.**
We'll have space for improving things once the site has launched, but for now are focussed on getting over the finish line.
To maintain a healthy noise/signal ration, we'll close issues that do not highlight specific bugs/issues.

Finally, please remember that spending an extra few seconds wording your bug report kindly can make a big difference to how those of us fixing these issues feel, how overwhelmed we get, how productive we are, and consequently how quickly this product gets launched. 
So please consider how what you write may be interpreted make an extra effort to be thoughtful 🙂

## Phased Beta

This is a phased beta.
That means two things:
1. Only some pages are ready to be tested at any time
2. Different feedback is requested at different points.

Please check the two lists below for what is in/out of scope at this stage.

### Pages/flows ready for testing

- **Page: Tracks list:** https://exercism.lol/tracks
- **Page: External Track:** https://exercism.lol/tracks/ruby
- **Page: Exercises List:** https://exercism.lol/tracks/ruby/exercises
- **Page: Concepts List:** https://exercism.lol/tracks/ruby/concepts
- **Page: Editor:** https://exercism.lol/tracks/ruby/concepts/two-fer/edit (You need to start the exercise for this link to work)
- **Page: Profile:** https://exercism.lol/profiles/iHiD
- **Flow: Creating a Profile:** https://exercism.lol/profiles/intro and https://exercism.lol/profiles/new

Any tooltips, dropdowns or modals that appear on these pages are **in scope**.
The results of any form submissions are also **in scope**.

Please only test things while being **logged in**. 

### Things to report

- **Bugs:** By bugs, we mean things not doing what they **should** do. Bugs include:
  - Errors (either full 500 pages or JS errors)
  - Does something not do what you expected when you clicked it.
  - Visual layout issues (for example, a tooltip not sitting above an page element)
  - Broken links that do not go to "#".
- **Things that are unclear:** If you're looking for a button and can't find it, feel unsure what to do next, don't know how to get "back", etc, then please tell us.
- **Track specific issues:** If something doesn't work for your track, but does work for other tracks, please tell us, regardless of whether it falls into the "do not report" category.
- **ETL issues:** Is something different on v3 to how it was in v2 in February. Data lost? Wrong? If so, please tell us.

### Please do *not* report
- Any feedback on copy / wording / spelling / grammar, etc
- Visual inconsistencies - the CSS isn't polished yet
- Accessibility issues - we'll do a full pass once everything is settled
- Links that go to "#"
- General feedback / opinions
- Mobile responsiveness issues.

## Reporting an issue

- Please use this repo to report issues.
- Ensure all issues state the page/flow name (as per the list from "Pages/flows ready for testing") and the issue using the format: `[Page: External Track] Lines between key features are missing`. If the issue is limited to a specific track, please add that in second square brackets, e.g. `[Page: External Track] [Ruby] Key Features not showing up`.
- Please keep issues factual. If you understand why something is breaking, please say, but the most helpful thing you can do is just to give us as many facts as possible.
- Please check for open issues first - every time we have to close duplicates is time wasted 
- Please include screenshots and JS console logs from dev tools, where possible.
