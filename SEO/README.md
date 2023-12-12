
# Technical SEO



## Baseline Optimization

Baseline Optimization forms the cornerstone of effective Technical SEO. It encompasses fundamental practices and settings that lay a strong foundation for enhancing your website's visibility in search engine results. In this section, we'll delve into the key components of Baseline Optimization.


---

### <input type="checkbox"/> 1. Page Title Tags 

- Keep them concise & meaningful | Follow the character limit (typically 50–60 characters, including spaces | Desktop = ~560px).
- Make sure to add and implement dedicated CMS items for Title tags in CMS page templates.

```markdown
<!-- Example Page Title Tag -->
<title>Home | Your Website</title>
```
---

### <input type="checkbox"/> 2. Page Descriptions

- Follow the character limit (50–160 characters, or up to 325 characters, including spaces).
- Make sure to add and implement dedicated CMS items for Title tags in CMS page templates.

```markdown
<!-- Example Page Description Tag -->
<meta name="description" content="Explore our latest products and services.">
```
---

### <input type="checkbox"/> 3. OpenGraph Image

Enhance your website's social media presence by incorporating OpenGraph images. These images dictate how your pages appear when shared on platforms like Facebook and Twitter.

```markdown
<!-- OpenGraph Image Tag -->
<meta property="og:image" content="https://example.com/images/og-image.jpg">
```
---

### <input type="checkbox"/> 4. URL Length

Keep your page URLs short, meaningful, and user-friendly. Ensure that auto-generated URLs for CMS page templates also adhere to these principles.

Example of a well-structured URL: https://example.com/about-us <br>
Example of a 'not so' well-structured URL: https://example.com/read-this-entire-blog-talking-about-us-how-we-work

---

### <input type="checkbox"/> 5. Duplicate Content Avoidance

Prevent duplicate content issues by using the no-index meta tag where necessary. This helps avoid the indexing of similar or redundant pages.

```markdown
<!-- No-Index Meta Tag -->
<meta name="robots" content="noindex, follow">
```
---


### <input type="checkbox"/> 6. Global Canonical Tag URL

Set the global canonical tag URL to specify the default live site URL. This instructs search engines about the preferred version of a page when multiple versions exist.

```markdown
<!-- Canonical Tag Example -->
<link rel="canonical" href="https://example.com/page">
```
---


### <input type="checkbox"/> 7. Sitemap Generation

Enable the auto-generation of a sitemap.xml file. This file lists all the important pages of your website, making it easier for search engines to discover and index content.

```markdown
User-agent: *
Sitemap: https://example.com/sitemap.xml
```
##### Add this code to the robots.txt section <br>Update the origin of the sitemap URL to the default domain set on Webflow

---


### <input type="checkbox"/> 8. Semantic Heading Structure

Maintain a semantic heading/header structure by assigning header tags (h1, h2, h3, etc.) based on their logical hierarchy & content relationships, and not based on their styling (e.g: font size). Ensure that each page has **only one h1** tag, and sub-header tags (h2, h3, etc.) follow a hierarchical structure.



<table>
  <tr>
    <td><img src="https://uploads-ssl.webflow.com/65773a7a7404baa4f10c65bf/65773c251fe5289755ff1003_heading%20structure%201.webp" alt="Image 1" width="325" height="325"></td>
    <td><img src="https://uploads-ssl.webflow.com/65773a7a7404baa4f10c65bf/65773c25f4cefa5e6eff4bfe_heading%20structure%202.webp" alt="Image 2" width="325" height="325"></td>
  </tr>
  <tr>
    <td><img src="https://uploads-ssl.webflow.com/65773a7a7404baa4f10c65bf/65773c2530759bf3c9a64b41_heading%20structure%203.webp" alt="Image 3" width="325" height="325"></td>
    <td><img src="https://uploads-ssl.webflow.com/65773a7a7404baa4f10c65bf/65773c255dbe2114c3caa222_heading%20structure%204.webp" alt="Image 4" width="325" height="325"></td>
  </tr>
</table>

---


### <input type="checkbox"/> 9. Alt Tags for Images

Add descriptive alt tags to images to provide context for visually impaired users and search engines. When images are purely decorative, set alt attributes accordingly to indicate their decorative nature.

```markdown
<!-- Image Alt Tag Example -->
<img src="image.jpg" alt="Illustration of a happy team working together">
<img src="decorative-image.jpg" alt="Decorative design element" aria-hidden="true">
```
---