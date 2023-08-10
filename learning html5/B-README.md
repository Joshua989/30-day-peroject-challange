Semantic HTML tags are HTML elements that carry meaning and convey the structure of a web page's content. They provide contextual information about the elements they wrap, making it easier for search engines, assistive technologies, and developers to understand the content's purpose and relationship within the page. Using semantic HTML tags improves accessibility, SEO, and code maintainability.

Here are some common semantic HTML tags and how to use them to structure a web page:

1. `<header>`: Represents the introductory content at the top of a section or a page. Typically contains the site logo, navigation, or other header elements.

2. `<nav>`: Defines a section of navigation links that lead to other pages or sections of the current page.

3. `<main>`: Represents the main content of the document. There should be only one `<main>` element per page, and it usually excludes headers, footers, and sidebars.

4. `<article>`: Represents a self-contained composition that can be independently distributed or syndicated. Commonly used for blog posts, news articles, or forum posts.

5. `<section>`: Defines a standalone section of content that is thematically related. It can contain headings, paragraphs, images, and other content.

6. `<aside>`: Represents content that is tangentially related to the main content and can be considered a sidebar or a separate section.

7. `<footer>`: Represents the footer of a section or the entire page. It often contains copyright information, contact details, and other related content.

8. `<figure>` and `<figcaption>`: Used together to represent media, such as images, diagrams, or videos, along with a caption that describes the media.

9. `<details>` and `<summary>`: Used to create interactive disclosure widgets that can be toggled to show or hide additional content.

Here's an example of how you might structure a simple web page using these semantic HTML tags:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Semantic HTML Example</title>
</head>
<body>
    <header>
        <h1>Welcome to My Site</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section>
            <h2>About Us</h2>
            <p>We are a team of passionate individuals...</p>
        </section>
        
        <section>
            <h2>Services</h2>
            <ul>
                <li>Web Development</li>
                <li>Graphic Design</li>
                <li>SEO Optimization</li>
            </ul>
        </section>
    </main>
    
    <aside>
        <h3>Latest News</h3>
        <p>Check out our latest blog posts...</p>
    </aside>
    
    <footer>
        <p>&copy; 2023 My Site. All rights reserved.</p>
    </footer>
</body>
</html>
```

By using semantic HTML tags, you provide a clear and meaningful structure to your web page's content, making it easier to understand and navigate for both humans and machines.