HTML & Web Accessibility | File Paths Best Practices
Restaurant Menu Activity
Activity: Restaurant Menu
Businesses of all kinds benefit from having a web presence-including our favorite restaurant! Even today, some restaurants do not have an online menu. Today, let's make a mini-website for a made-up Thai restaurant we'll call H-Thai-ML.

H-Thai-ML Banner Logo
Part One: Grab a Classmate or Two
It's both fun and useful to write code in pairs or small groups. A big part of your future role as a software developer will involve writing code with others and working as part of a team. If you end up doing this assignment during class, your instructor will assign you to groups of two or three people. If you end up doing it as homework, the group aspect is optional but highly recommended!

Tip: As you go through this activity, make sure everyone in your group understands how you reached your goals along the way to create the finished product.

Part Two: Flex Your UX Muscles
What are the most important aspects of a restaurant website? Think about the personas who might be visiting the site. (A persona is a sample user who is a good proxy for the needs of a larger group of users.)

Consider the following questions:

What does a user want when they visit a restaurant's website?
How long does a user want to spend on the site?
What information is the most important visually?
Have you ever visited a restaurant website? If so, was there any part of the experience that either frustrated or delighted you?
Part Three: Plan
You may have come up with several different needs for a typical restaurant website. Are they included in the list below?

Access to the menu
Images of food
Contact information for ordering
Online ordering
Any changes related to holidays, closures, or COVID-19
Information about authenticity or how the restaurant started
We aren't quite there on the online ordering part-that will require building a back-end to handle the data (we'll learn to do that later in the course). However, we are equipped to accomplish the rest of the tasks!

Here's the Plan
Let's make a website that has at least four pages and a navbar that will exist on each page:

Homepage (index.html)
Menu page (menu.html)
About page (about.html)
Contact page (contact.html)
A navbar (copy onto each page)
Part Four: Start Coding!
You can find starter code on this repository's master branch.

Requirements
Note: CSS is provided for you. If you're following the steps correctly, you will automatically see elements that align with the style of the restaurant.

Make sure to put your page content (other than navbar, banner, and footer) in the main tag. We'll learn more about main tags later, but for now, it's just something we'll use for styling and organizational purposes.

The Finished Product Will Look Similar to This:
finished product
Navbar & Banner Image
The navbar and banner image may be a good place to start, since they will go on every page. Once you get them right on one page, you can copy them over to the other pages. Both the navbar and the banner image should be full-width, and the navbar should include links to each of the four pages. These will be relative links in anchor tags.

If you forgot how to make a navbar, refer back to the navbar activity from earlier.

For making images, divs, and other elements full-width, we will need a small amount of CSS. Assuming your navbar is using a nav tag, the CSS provided in the starter code will work. It looks something like this:

undefinedClick here to copy
The banner image is the banner.jpg image found in the assets folder under the images subfolder. You can replace it with a custom banner if you would like.

Homepage
The homepage should use the banner.png image provided in the starter code's assets folder. This banner should be full-width.

Images can use the same width property as our navbar above; however, we also want images to scale. We can set the height property to auto to preserve the aspect ratio (this means that the image won't get stretched out). Assuming your banner img tag has an id attribute of banner, your HTML and CSS code snippets might look like this:

undefinedClick here to copy
The CSS provided has these properties to make it scale like we want:

undefinedClick here to copy
Next, let's make an h1 tag with the restaurant name and an h2 tag with a one-sentence catchphrase or jingle. Feel free to get creative or punny with this!

Next, let's display three boxes (divs) that tell you about each of the options for obtaining food from the restaurant. These options are Dine In, Take Out, and Delivery. Each of these options should be in h3 tags inside of each of the three divs.

Go ahead and make those three boxes display as inline-block and set some widths and margins so they display side-by-side and centered. In order to set these styles on ONLY those three divs and not any other divs on your page, let's give this div a class name of service. Your HTML will look like this:

undefinedClick here to copy
You can use the CSS in the starter code for the service divs. Here's the important part:

undefinedClick here to copy
Let's finish out the homepage by including a nice image of the restaurant setup. You can find an image in the assets folder called tables-in-restaurant.jpg.

About Page
An about page provides background on the restaurant, such as why the owner decided to open a restaurant. It could also mention the authenticity of the cuisine or information about the original location of the flagship restaurant, if it is now a chain.

Let's include an h1 tag containing the text About Us, an h2 tag that contains the text Locations, and an h2 tag containing the text Origin Story.

Under Locations, make an unordered list and include at least four locations that you make up.

Under Origin Story, place the image about.png (or use another image of your choice). Next, choose one of the locations from your list as the flagship location. Then, include a paragraph tag with a short story you make up about why the owner opened the restaurant in that particular location. You can make up a creative story or just use lorem ipsum text if you would like.

Contact Page
The contact page should begin with the hours of operation. This is provided in the starter code. Next, under the Contact Info h2 tag, include a phone number, address, and a customer service email that you make up on separate lines.

Let's select Font Awesome icons to represent the phone number, email, and address. For example, we could use fa-phone for a phone icon. You can check out envelope for email and map-marker or address-card for the address, or select other icons that you like.

Remember, you can include the Font Awesome icons via their CDN link:

undefinedClick here to copy
Menu Page
Make an h1 tag that contains the text Our Menu. Next, we're going to want to make several different sections for menus. Let's make multiple h2 tags containing the text Appetizers, Lunch, Dinner, Dessert, Beverages, and Side Orders.

Under each of your h2 tags, make a table tag. Each table header should include the column headers Name and Price.

The list of menu items and prices is already provided in your starter code, but is not yet formatted into a table with proper table rows and cells. That's your job!

All Done?
Feel free to check your answers against the solution code, then tackle the bonus below.

Bonus
All done? Here are some ideas for bonus activities:

Make your navbar highlight the current page in some way. For example, you might highlight the link in the navbar in a different color based on what page it is.
Include a full-width banner at the top of every page that announces a closure based on the next upcoming holiday.
Find a star icon in the Font Awesome icons. Use it to highlight at least three menu items you deem "Most Popular."
Find a fire icon in the Font Awesome icons. Use it to highlight at least three menu items you deem "Most Spicy."
Make a nice footer for your pages. Try to create CSS that enables it to match the color scheme.
When you're done, you can take a look at the bonus solution code.

Acceptance Criteria
When a user clicks a link in the nav bar, the appropriate page is shown.
When a user visits the menu page, they can see a list of menu items and their prices.
Given that a user is on the about page, they can see an image, headers, and text.
Given that a user is on the contact page, they can see each contact type with a corresponding Font Awesome icon.
Before submitting, make sure you do a self review of your code, check for formatting, spelling, include comments in your code, and ensure you have a healthy commit history.

Make sure to submit your github repository link on the submission page.