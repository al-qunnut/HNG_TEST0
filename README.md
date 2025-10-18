Profile Card — Simple README

This project is a small profile card built with plain HTML, CSS and vanilla JavaScript. The code is written for clarity and to be easy to test.

Files
- index.html: The whole project. It contains markup, styles, and a small script.

How the code is organized
- The card is wrapped in an <article> element with data-testid="test-profile-card".
- The user name is in an <h2> with data-testid="test-user-name".
- The biography is in a <p> with data-testid="test-user-bio".
- The current time is shown in the element with data-testid="test-user-time". The script writes Date.now() (milliseconds) and updates it every second.
- The avatar is inside a <figure>. The <img> element includes data-testid="test-user-avatar" and has an alt attribute.
- Social links are in a <ul> with data-testid="test-user-social-links". Each link opens in a new tab (target="_blank") and uses rel="noopener noreferrer" for security.
- Hobbies and dislikes are two lists inside separate <section> elements with data-testid="test-user-hobbies" and data-testid="test-user-dislikes".

Accessibility and behavior notes
- All interactive items (links) are keyboard-focusable. Focus styles are provided so keyboard users can see where focus is.
- The layout is responsive. On small screens the content stacks vertically and the hobbies/dislikes wrap into badge-like items.
- The time is updated using Date.now() so automated tests can read a millisecond timestamp.

How to view locally
1. Open the folder in your file explorer.
2. Double-click `index.html` or open it with your browser.

No build step is required. The project runs in any modern browser.
