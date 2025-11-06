practical writeup:

o create a simple mobile website using jQuery Mobile framework that is responsive and mobile-friendly.

🧩 Software/Tools Required:

Web Browser (Google Chrome, Firefox, etc.)

Text Editor (VS Code / Sublime / Notepad++)

Internet connection (for jQuery Mobile CDN)

🧱 Theory:

jQuery Mobile is a framework built on top of the jQuery library designed to simplify the creation of responsive, touch-friendly web pages for smartphones and tablets.
It provides:

Pre-styled UI components (buttons, lists, dialogs)

Responsive design

Page navigation system

Theming and transitions
☁️ Deployment / Hosting (AWS)
1. AWS Elastic Beanstalk:

Go to AWS Management Console
.

Select Elastic Beanstalk → Create New Application.

Choose Web Server Environment.

Upload your HTML file in a .zip folder.

Deploy and access the provided AWS URL.

2. AWS S3 (Static Hosting):

Create an S3 bucket.

Enable Static Website Hosting.

Upload your .html file.

Copy the Public URL to access your hosted site
In this practical, we successfully created a mobile-friendly website using the jQuery Mobile framework.
The website demonstrates the use of multiple pages within a single HTML file, smooth page navigation, responsive design, and mobile-optimized UI components such as buttons, headers, footers, and list views.

Through this experiment, we learned how jQuery Mobile simplifies web development for mobile devices by providing built-in UI themes, transitions, and touch-friendly controls.
Finally, by deploying the website on AWS (Elastic Beanstalk or S3), we understood how to host and make the mobile website accessible online — completing both the development and deployment process of a modern web application.




VIVA QUESTION

🟩 HTML Basics

1. What does <!DOCTYPE html> mean?
→ It declares that the document type is HTML5.

2. What is the purpose of the <html> tag?
→ It represents the root of an HTML document.

3. What does the <head> section contain?
→ It contains metadata, title, CSS, and script links not visible to users.

4. What does <meta charset="UTF-8"> do?
→ It ensures the webpage supports all languages and symbols.

5. What is the use of the <title> tag?
→ It sets the name shown on the browser tab.

6. What is the purpose of <meta name="viewport" content="width=device-width, initial-scale=1">?
→ It ensures proper scaling and responsiveness on mobile screens.

7. What is the difference between <head> and <body>?
→ <head> has information about the webpage; <body> has the visible content.

8. What does <h1> to <h6> represent?
→ They represent headings, from largest (<h1>) to smallest (<h6>).

9. What is the purpose of <p> tag?
→ It defines a paragraph of text.

10. What is the use of <img> tag?
→ It displays an image on a web page.

🟦 jQuery and jQuery Mobile

11. What is jQuery?
→ A JavaScript library that simplifies HTML DOM manipulation and events.

12. What is jQuery Mobile?
→ A framework built on top of jQuery for creating mobile-friendly web apps.

13. Why do we include jQuery before jQuery Mobile?
→ Because jQuery Mobile depends on the jQuery library.

14. What is the purpose of data-role attribute in jQuery Mobile?
→ It tells jQuery Mobile what type of element to render (e.g., page, header, footer).

15. What does data-role="page" mean?
→ It defines a new page in the jQuery Mobile app.

16. What is the use of data-role="header" and data-role="footer"?
→ They define the top (header) and bottom (footer) sections of a page.

17. What is the use of data-role="button"?
→ It converts a normal link or input into a mobile-friendly button.

18. What is the role of data-icon in jQuery Mobile?
→ It adds an icon next to the button text.

19. What does data-theme="b" mean?
→ It applies theme “b” (a dark color theme).

20. What is the difference between data-role="page" and data-role="dialog"?
→ page creates a normal page; dialog creates a popup-like page.

🟨 Navigation and Layout

21. How do you navigate between pages in jQuery Mobile?
→ By linking to page IDs using <a href="#pageID">.

22. Why do we use multiple div tags with data-role="page"?
→ To define multiple pages in a single HTML file.

23. What is data-position="fixed" used for?
→ It keeps the header or footer fixed while scrolling.

24. What is the purpose of <div role="main" class="ui-content">?
→ It defines the main content area of the page with jQuery Mobile styling.

25. What is a listview in jQuery Mobile?
→ A widget that formats lists into mobile-friendly styles.

26. What is the use of data-inset="true" in listview?
→ It adds rounded corners and margins around the list.

27. What is the difference between <a> and <button> in HTML?
→ <a> is for navigation; <button> is for form actions or events.

28. Can we include images in jQuery Mobile pages?
→ Yes, using <img> tag, optionally styled with CSS.

29. Why is jQuery Mobile good for mobile apps?
→ It provides touch-friendly UI, automatic scaling, and responsive layouts.

30. What is the use of role="main"?
→ It defines the primary content area of the page for accessibility.

🟥 Forms and Inputs

31. What is the use of <form> tag?
→ To collect and submit user input data.

32. What does <label for="name"> mean?
→ It connects a label to an input field with the same id.

33. What is the purpose of type="text" in <input>?
→ It creates a single-line text field.

34. What is type="email" used for?
→ It accepts only valid email format input.

35. What does <textarea> do?
→ It allows users to enter multi-line text input.

36. What is the function of <input type="submit">?
→ It submits the form data to a server or script.

37. How can we make input fields required?
→ By adding the required attribute.

38. Can jQuery Mobile enhance form elements automatically?
→ Yes, it styles them using its built-in CSS and JS.

39. What is a placeholder attribute?
→ It shows hint text inside an input box until the user types.

40. How can you reset a form?
→ Using <input type="reset">.

🟪 CSS and Custom Styling

41. What is the purpose of CSS?
→ CSS is used to style and format HTML elements.

42. What is the syntax of CSS?
→ selector { property: value; }

43. How do you link an external CSS file?
→ Using <link rel="stylesheet" href="style.css">.

44. What is a class selector in CSS?
→ It starts with a . (dot) and is applied using the class attribute.

45. What is the purpose of inline CSS?
→ To style a specific element using the style attribute directly.

46. Which is better: inline or external CSS?
→ External CSS (it’s reusable and cleaner).

🟫 Deployment and Hosting (AWS)

47. What is AWS Elastic Beanstalk?
→ A cloud service used to deploy and manage web applications automatically.

48. What is AWS S3?
→ A cloud storage service that can also host static websites.

49. How do you deploy a jQuery Mobile site on AWS Elastic Beanstalk?
→ Zip your project folder → Upload it in Elastic Beanstalk → AWS gives a live URL.

50. Why deploy a project on AWS?
→ It provides scalability, reliability, and global availability for your website.
