# 01 HTML, CSS, and Git: Code Refactor

The task for this assignment was to perform a refactoring of the given code in order to achieve a user story that matched the given acceptance criteria. Those guidelines are listed below.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning 
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element 
THEN I find a concise, descriptive title
```

## What changes were executed

```
Semantic HTML elements were added to replace <div> elements in order to create a more meaningful codebase. <div> elements were updated to <header>, <section>, and <footer> elements. 

The structure of the HTML follow a logical structure.

The icon and image elements were updated to have alt="" attributes in order to make them more accessible for people with disabilities. 

The title a concise and descriptive title. It is now called Horiseon.

The link for Search Engine Optimization wasn't working and in order to get it to work id="search-engine-optimization" was added to the content section <div>.

Mass consolidation of CSS instructions. Notes are included above pieces that were consolidated.



