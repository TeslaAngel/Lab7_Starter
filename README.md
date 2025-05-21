# Lab7_Starter

Contributor: Mohan Dong

Answers:
1. Within a Github action that runs whenever code is pushed. This ensures consistency and efficiency of the test (since tests are required before merging) and validates pull requests, which is important for avoid disturbance on the continuous delivery of the main branch.
2. No, this should be done via an automated unit test.
3. Navigation mode analyzes a page right after it loads, and will consider factors like load time for the initial state of the page; however, since it starts right after the page is loaded, it can't analyze interactive components that changes by user behaviors, like textfield input. \
On the other hand, snapshot mode captures a specific moment of the webpage for analyzation. While it doesn't consider the initial load time of the page, it can be used to analyze interactive components and thus is good at finding accessibility issues.
4. 1. Proper size images: the images of the shop page are larger than they appear on the actual webpage, which increases the load time.
4. 2. Serve images in next gen formats: while the jpeg format we are using is commonly used in web development, there exists more efficient image formats like Webp and AVIF that offers even better compression and can further reduce the load time and data consumption.
4. 3. Include a <meta name="viewport"> tag with width or initial-scale, which prevents a 300 ms delay to user input while optimizes the page for mobile screen sizes.