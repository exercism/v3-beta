# The Exercism V3 Beta

We're nearly ready to launch v3 of Exercism, culminating nearly two years of hard work 🎉

We are running a [phased beta of the website](https://exercism.lol) and we'd love your help in highlighting any bugs or issues!
**Please read this document carefully before getting started.**

Also, please note that the purpose of this website is to find things that are broken, so that we can ship this new version of the platform.
**It is not to assertain peoples thoughts or opinions on v3 in general, or to get ideas for improvements.**
We'll have space for improving things once the site has launched, but for now are focussed on getting over the finish line.
To maintain a healthy noise/signal ratio, we'll close issues that do not highlight specific bugs/issues.

We recommend trying the site using Chrome if you want the best experience. 
Before launching, we'll get it working on all browsers, but we use Chrome internally, so your experience will be the most "as expected" if you also use Chrome.

Finally, please remember that spending an extra few seconds wording your bug report kindly can make a big difference to how those of us fixing these issues feel, how overwhelmed we get, how productive we are, and consequently how quickly this product gets launched. 
So please consider how what you write may be interpreted make an extra effort to be thoughtful 🙂

## Phased Beta

We are now in the final phase of the beta. 
All pages are now in scope on desktop (not on mobile).

### Things to report

- **Bugs:** By bugs, we mean things not doing what they **should** do. Bugs include:
  - Errors (either full 500 pages or JS errors)
  - Does something not do what you expected when you clicked it.
  - Visual layout issues (for example, a tooltip not sitting above an page element, or two elements overlapping)
  - Broken links that do not go to "#".
- **Things that are unclear:** If you're looking for a button and can't find it, feel unsure what to do next, don't know how to get "back", etc, then please tell us.
- **Track specific issues:** If something doesn't work for your track, but does work for other tracks, please tell us, regardless of whether it falls into the "do not report" category.
- **ETL issues:** Is something different on v3 to how it was in v2 in February. Data lost? Wrong? If so, please tell us.
- Any feedback on copy / wording / spelling / grammar, etc
- Visual things that are wrong (e.g. where there is white text on a white button)

### Please do *not* report
- Accessibility issues - we'll do a full pass once everything is settled
- Links that go to "#"
- General feedback / opinions
- Mobile responsiveness issues.

## Reporting an issue

- Please use the [v3-beta repo](https://github.com/exercism/v3-beta) to report issues.
- Ensure all issues state the page/flow name (as per the list from "Pages/flows ready for testing") and the issue using the format: `[Page: External Track] Lines between key features are missing`. If the issue is limited to a specific track, please add that in second square brackets, e.g. `[Page: External Track] [Ruby] Key Features not showing up`.
- Please keep issues factual. If you understand why something is breaking, please say, but the most helpful thing you can do is just to give us as many facts as possible.
- Please check for open issues first - every time we have to close duplicates is time wasted 
- Please include screenshots and JS console logs from dev tools, where possible.

## Changelog

### 14th May 2021

First version.

### 21st May 2021

**Newly in scope:**

- Page: Exercise/Iterations

**New functionality:**

- Exercise makers modal (click on authors/contributors on an exercise page)
- Test results (click on "Failed" in mentoring header or community solution)
- Editor changed to CodeMirror

### 22nd May 2021

**Newly in scope:**

- Page: Exercise/Overview

### 14th June 2021

**Newly in scope:**

- Page: Exercise/Mentoring
- Page: Concept/Overview
- Page: Contributors/Contributing
- Page: Contributors/Tasks
- Page: Mentoring/Workspace
- Page: Mentoring/Queue
- Page: Mentoring/Testimonials
- Page: Journey/Badges

### 15th June 2021

**Newly in scope:**

- Page: Track (Joined)

### 24th June 2021

**Newly in scope:**

- Flow: Exercism/Mentoring
- Flow: Mentoring/Discussion


### 3rd July 2021

**Newly in scope:**
- Page: Settings/Account
- Page: Settings/API

### 6th August 2021

- All pages are in scope
