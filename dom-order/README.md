Tabbing around the page should reveal a mixed up tab order. Read through the
`index.html` and see if there are any places where elements may be in the wrong
order. If something looks out of place see if you can fix it so the tab order
works as expected. If you get stuck you can refer to the `solution` directory.

aaronbnb: I changed the CSS to reach to fix the DOM order, which meant having sign up form underneath the header. Then for practice, reset the CSS and changed the HTML to fix the DOM order. Can be done either way, but changing HTML may be preferable since WCAG 2.0 Guideline, Perceivable Section, 1.3.2 states that DOM order should rely on structural markup, not CSS, to return correct order.
