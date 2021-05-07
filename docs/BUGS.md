# Bugs and fixes
- Booking Page
  Bug: on submitting the booking form, URL used to change with some query strings.
  Fix: Form method used as post with empty action. removed mthod attribute from form and changed action to /booking, which fixed the issue.

- Mobile Pages
  Bug: On clicking hamburger menu, not able to see the navigation menu as a popover/slide in menu.
  Fix: Without Javascript, achieving the modal/popover is difficult. I had to implemente it as a separate page

  - The Logo 
  Bug: The logo at the top left of all the pages would not take user back to the home page
  Fix: Re-routed the route