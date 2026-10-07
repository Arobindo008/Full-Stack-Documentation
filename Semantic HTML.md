## Importance of Semantic HTML

- **Structural hierarchy for heading elements**: It is important to use the correct heading element to maintain the structural hierarchy of the content. The `h1` element is the highest level of heading and the `h6` element is the lowest level of heading. Skipping heading levels disrupts the logical hierarchy for screen readers and hinders accessibility.

- **Presentational HTML elements**: Elements that define the appearance of content. Ex. the deprecated `center`, `big` and `font` elements.

- **Semantic HTML elements**: Elements that hold meaning and structure. Ex. `header`, `nav`, `figure`.
## Semantic HTML Elements

- **Header element**: used to define the header of a document or section.
<header>

<h1>CatPhotoApp</h1>

<p>Welcome to our cat gallery.</p>

</header>

---

 - **Main element**: used to contain the main content of the web page.
 <main>

<section>

<h2>Cat Photos</h2>

<p>Browse adorable cat pictures.</p>

</section>

</main>

---

- **Section element**: used to divide up content into smaller sections.


---


-  **Navigation Section (`nav`) element**: represents a section with navigation links.

- **Article (`article`) element**: used to represent self-contained, independent content that can stand alone, such as a blog post or news article.

- **Figure element**: used to contain illustrations and diagrams.

-  **Emphasis (`em`) element**: marks text that has stress emphasis.

- **Idiomatic Text (`i`) element**: used for highlighting alternative voice or mood, idiomatic terms from another language, technical terms, and thoughts.The `lang` attribute inside the open `i` tag is used to specify the language of the content. In this case, the language would be French. The `i` element does not indicate if the text is important or not, it only shows that it's somehow different from the surrounding text.
	- **Choosing CSS over `i`/`em`**: since `i` and `em` carry meaning, text that only needs to look italic for presentation purposes should be styled with CSS instead.
    
     - **Strong Importance (`strong`) element**: marks text that has strong importance.