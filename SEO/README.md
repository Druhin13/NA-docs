# Technical SEO

<br>

## Baseline Optimization

Baseline Optimization forms the cornerstone of effective Technical SEO. It encompasses fundamental practices and settings that lay a strong foundation for enhancing your website's visibility in search engine results. In this section, we'll delve into the key components of Baseline Optimization.


<br>

---

### 1. Page Title Tags

Page titles play a vital role in SEO. They should be concise (typically 50–60 characters, including spaces) and accurately represent the content of each page. Implementing dedicated CMS items for Title tags in CMS page templates can streamline this process.

```markdown
<!-- Example Page Title Tag -->
<title>Home | Your Website</title>
```
---

### 2. Page Descriptions

Page descriptions offer a brief summary of a page's content. Craft informative and engaging descriptions (50–160 characters, or up to 325 characters, including spaces). Consider using dedicated CMS items for Description tags in CMS page templates.

```markdown
<!-- Example Page Description Tag -->
<meta name="description" content="Explore our latest products and services.">
```
---

### 3. OpenGraph Image

Enhance your website's social media presence by incorporating OpenGraph images. These images dictate how your pages appear when shared on platforms like Facebook and Twitter.

```markdown
<!-- OpenGraph Image Tag -->
<meta property="og:image" content="https://example.com/images/og-image.jpg">
```
---

### 4. URL Length

Keep your page URLs short, meaningful, and user-friendly. Ensure that auto-generated URLs for CMS page templates also adhere to these principles.

Example of a well-structured URL: https://example.com/about-us <br>
Example of a 'not so' well-structured URL: https://example.com/read-this-entire-blog-talking-about-us-how-we-work

---

### 5. Duplicate Content Avoidance

Prevent duplicate content issues by using the no-index meta tag where necessary. This helps avoid the indexing of similar or redundant pages.

```markdown
<!-- No-Index Meta Tag -->
<meta name="robots" content="noindex, follow">
```
---


### 6. Global Canonical Tag URL

Set the global canonical tag URL to specify the default live site URL. This instructs search engines about the preferred version of a page when multiple versions exist.

```markdown
<!-- Canonical Tag Example -->
<link rel="canonical" href="https://example.com/page">
```
---


### 7. Sitemap Generation

Enable the auto-generation of a sitemap.xml file. This file lists all the important pages of your website, making it easier for search engines to discover and index content.

```markdown
User-agent: *
Sitemap: https://example.com/sitemap.xml
```
<div style="color: #E3B774;  font-size: 80%;">
    Add this code to the robots.txt section<br>
    Update the origin of the sitemap URL to the default domain set on Webflow
</div>

---


### 8. Semantic Heading Structure

Maintain a semantic heading/header structure by assigning header tags (h1, h2, h3, etc.) based on their logical hierarchy & content relationships, and not based on their styling (e.g: font size). Ensure that each page has **only one h1** tag, and sub-header tags (h2, h3, etc.) follow a hierarchical structure.



<table>
  <tr>
    <td><img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%201.png" alt="Image 1" width="325" height="325"></td>
    <td><img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%202.png" alt="Image 2" width="325" height="325"></td>
  </tr>

  <tr>
    <td><img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%203.png" alt="Image 3" width="325" height="325"></td>
    <td><img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%204.png" alt="Image 4" width="325" height="325"></td>
  </tr>
</table>


<!-- <div style="display: flex; flex-wrap: wrap; gap: 10px; width: 70%">
    <div style="flex: 1; width: 50%;">
        <img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%201.png" alt="Image 1" style="width: 100%;">
    </div>
    <div style="flex: 1; width: 50%;">
        <img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%202.png" alt="Image 2" style="width: 100%;">
    </div>
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; width: 70%">
    <div style="flex: 1; width: 50%;">
        <img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%203.png" alt="Image 3" style="width: 100%;">
    </div>
    <div style="flex: 1; width: 50%;">
        <img src="https://druh.in/NA-docs/SEO/assets/heading%20structure%204.png" alt="Image 4" style="width: 100%;">
    </div>
</div> -->


---


### 9. Alt Tags for Images

Add descriptive alt tags to images to provide context for visually impaired users and search engines. When images are purely decorative, set alt attributes accordingly to indicate their decorative nature.

```markdown
<!-- Image Alt Tag Example -->
<img src="image.jpg" alt="Illustration of a happy team working together">
<img src="decorative-image.jpg" alt="Decorative design element" aria-hidden="true">
```
---