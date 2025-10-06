# Introduction-to-CSS3

The fundamentals of adding style to web pages using CSS (Cascading Style Sheets).

Understanding Browser Differences

Different browsers may render the same HTML file differently due to varying support for tags and default styles.
Users often prefer styled pages over plain default looks, prompting the need for CSS.
Inline Styles vs. CSS

Inline styles can be added directly to HTML tags but mix content with style, making future changes cumbersome.
CSS allows for a cleaner separation of content and style, enabling the application of rules to multiple elements.
Writing CSS Rules

CSS rules consist of a selector (e.g., tag names like h1 or p), properties (e.g., color, background color), and values (e.g., blue).
Proper syntax is crucial in CSS; mistakes can lead to rendering issues, unlike HTML which is more forgiving.
Applying Styles

Internal style sheets are useful for single-page styling, while external style sheets allow for consistent styling across multiple pages.
External style sheets are saved in a separate .CSS file and linked in the HTML, making it easy to update styles site-wide.

The concept of Cascading Style Sheets (CSS) and how styles are applied to web pages in a specific order of precedence.

Understanding CSS Precedence

The browser first uses its default styles for elements like headings.
It then checks for external stylesheets, followed by internal styles, and finally inline styles, which have the highest priority.
Order of Styles

If multiple styles are defined for the same element, the most recent style in the code takes precedence.
The !important attribute can be used to enforce a specific style, overriding other rules.
Examples of Styling

Inline styles affect only the specific element they are applied to, while internal styles can apply to multiple elements.
External stylesheets help organize code and can style multiple pages consistently.
Separation of Content and Style

Emphasizes the importance of keeping content (HTML) separate from styling (CSS) for better organization and maintainability.
The lecture concludes with a demonstration of how different styles can dramatically change the appearance of the same HTML content.
