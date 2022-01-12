# **Acceptance Criteria (AC) Standards & Best Practices**
Detailed checklist items for each main page type & resources to keep in mind while developing.

**Arch strives for WCAG 2.0 Level AA: Acceptable compliance.**
This conformance level is used in most accessibility rules and regulations around the world, including the ADA. To meet WCAG 2.0 Level AA conformance, the website is usable and understandable for the majority of people with or without disabilities.<sup>[1](https://www.accessiblemetrics.com/blog/what-are-the-levels-of-wcag-compliance/)</sup>

## **Resources**
[Project A11y Checklist](https://www.a11yproject.com/checklist/)
_* Based on WCAG Standards, but written and organized much more clearly_

## **Checklists**
> ### **Global Code Checklist**
> _Global code is code that affects your entire website or web app._\
\
> **Required ACs**
> * [ ] Validate your HTML - consistent experience across all browsers
> * [ ] Ensure that viewport zoom is not disabled - Resizing text allowed
> * [ ] Ensure a linear content flow
> * [ ] Avoid using the autofocus attribute
> * [ ] Refrain from using title attribute in any tags - instead use name, role, value when possible (except for iframes)\
\
**Nice To Haves**
> * [ ] Use landmark elements to indicate important content regions

> ### **Keyboard Checklist**
> * [ ] Make sure there is a visible focus style for interactive elements that are navigated to via keyboard input
> * [ ] Check to see that keyboard focus order matches the visual layout
> * [ ] Remove invisible focusable elements

> ### **Images Checklist**
> * [ ] Make sure that all img elements have an alt attribute
> * [ ] Make sure that decorative images use null alt (empty) attribute values
> * [ ] Provide a text alternative for complex images such as charts, graphs, and maps
> * [ ] For images containing text, make sure the alt description includes the image's text

> ### **Headings Checklist**
> * [ ] Use heading elements to introduce content
> * [ ] Use only one h1 element per page or view
> * [ ] Heading elements should be written in a logical sequence
> * [ ] Don't skip heading levels

> ### **Controls Checklist**
> * [ ] Use the a element for links
> * [ ] Ensure that links are recognizable as links
> * [ ] Ensure that controls have :focus states
> * [ ] Use the button element for buttons
> * [ ] Provide a skip link and make sure that it is visible when focused
> * [ ] Identify links that open in a new tab or window

> ### **Appearance Checklist**
> * [ ] Check your content in specialized browsing modes
> * [ ] Increase text size to 200%
> * [ ] Double-check that good proximity between content is maintained
> * [ ] Make sure color isn't the only way information is conveyed
> * [ ] Make sure instructions are not visual or audio-only
> * [ ] Use a simple, straightforward, and consistent layout

> ### **Color Contrast Checklist**
> * [ ] Check the contrast for all normal-sized text
> * [ ] Check the contrast for all large-sized text
> * [ ] Check the contrast for all icons
> * [ ] Check the contrast of borders for input elements (text input, radio buttons, checkboxes, etc.)
> * [ ] Check text that overlaps images or video
> * [ ] Check custom ::selection colors

## **ARCH**
* [ ] Provide a unique title in the root html, contained in the document's head element
* [ ] Use a lang attribute on the html element

## **Homepage**
* [ ] Check off all **Required ACs** items of the following checklists:  (found above)
> * [ ] Global Code
> * [ ] Keyboard
> * [ ] Images - _(skip charts and graphs for now, let’s consider that a separate initiative)_
> * [ ] Headings
> * [ ] Controls
> * [ ] Appearance
> * [ ] Color Contrast
* [ ] Content - Making sure all buttons and links are accessible, unique and descriptive 
* [ ] Search Bar input area is accessible by Keyboard tabbing
* [ ] Appzi Feedback button is accessible by Keyboard tabbing
* [ ] Users are able to complete tasks/experience page by Keyboard and by Screen Reader
* [ ] If time allows: Check off as many nice-to have items of the checklists above
