# Day 6 challenge of 50 days HTML Learning ✨💥
## TOPIC :
- **Day 6:** Links and Navigation Creating Hyperlinks with a .Absolute vs.relative URLs.Anchor.
# Links and Navigation

## Creating Hyperlinks

Hyperlinks are essential for navigating between different pages on the web. They can be created using the `<a>` tag in HTML. 

## Syntax

`<a href="URL">Link Text</a>`

- **Attributes:**

  `href` : specifies the URL of the link

  `title` :  specifies a tooltip or a title for the link

  `target` : specifies where to open the linked document (e.g., _blank for a new tab)


- **Examples:**

     Linking to an External Website

    `<a href="https://www.example.com">Visit Example</a>`

     Linking to an Internal Page

    `<a href="about.html">About Us</a>`

    Linking to an Email Address

    `<a href="mailto:user@example.com">Contact Us</a>`

    Linking to a Phone Number

    `<a href="tel:+1234567890">Call Us</a>`

## Absolute vs Relative URLs

Absolute URLs
An absolute URL contains the full path, including the protocol (http, https), domain name, and path to the resource.

- **Examples:**

   `<a href="https://www.example.com/page.html">Example Absolute URL</a>`

- **Advantages:**

   Easy to understand and maintain.

   Works regardless of the current page's location.

- **Disadvantages:**

   Can be lengthy and cumbersome.

   May not be suitable for local development or testing.

- **Relative URLs:**

   A relative URL is a partial path that is relative to the current page's location.

- **Examples:**

   `<a href="page.html">Example Relative URL</a>`

- **Advantages:**

  Shorter and more concise.

  Suitable for local development or testing.

  Easier to maintain and update.

- **Disadvantages:**

  May not work correctly if the current page's location changes
Requires careful planning and organization

- **Anchors:**
Anchors allow you to link to a specific part of a page. This is particularly useful for long pages where you want to direct users to a specific section.

## Creating an Anchor

`<a href="#section1">Go to Section 1</a>`

## Defining the Anchor

`<h2 id="section1">Section 1</h2>`

- **Examples:**

  Linking to an Anchor on the Same Page

  `<a href="#contact">Contact Us</a>`

<h2 id="contact">Contact Information</h2>

  Linking to an Anchor on a Different Page

 `<a href="about.html#team">Meet Our Team</a>`

 `<h2 id="team">Our Team</h2>`

