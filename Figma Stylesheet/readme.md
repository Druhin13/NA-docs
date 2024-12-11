
# Figma Stylesheet Documentation for Designers

This documentation is your guide to correctly using and filling out the **stylesheet template** within your Figma project file. The stylesheet acts as the main source of truth for your Figma file and is a key part of the handoff workflow from Figma to Webflow, designed to simplify the process while ensuring consistency and precision across our projects.

---

## **Getting Started**

### Step 1: Add the Stylesheet Template
1. Copy the **stylesheet template**.
2. Paste it into the **Figma file** of your project, preferably on a dedicated page named "Stylesheet" or something similar for easy reference.

---

## **Understanding the Stylesheet**

The stylesheet is divided into **2 main sections**:
1. **Typography Classes**: Defines all the text styles.
2. **Color Variables**: Includes all color definitions categorized by usage.

These sections should be filled out thoroughly for every project to ensure a seamless design-to-development handoff.

---

## **Typography Classes**

### **1. Typeface**
- Begin by adding or updating the **typeface(s)** used in the project.
- Use the **Typeface Header** in the template to list all typefaces (e.g., Roboto, Inter, etc.).
- If your project uses multiple typefaces, duplicate the header and add new ones.

---

### **2. Text Styles**
#### Creating and Editing Text Styles:
- **Location**: Use the **Local Styles** section in the **Properties Panel** on the right-hand side of the Figma window.
- **Naming Convention**: Follow the pattern `titleX-Y-breakpoint`.

#### Naming Breakdown:
- **X**: Represents the primary usage, e.g., `title1`, `title2`, ... `title13`, etc.
- **Y**: Represents a variant of the base style, e.g., `title1-2` for an alternate version.
- **Breakpoint**: Specifies the responsive breakpoint (e.g., desktop, tablet, mobile).

#### Examples:
- `title1-1-desktop`: Default title1 heading for desktop.
- `title1-2-desktop`: A variation of the title1 heading for desktop.
- `title2-1-mobile`: Default title2 for mobile.
- `title2-2-tablet`: A variation of the title2 for tablet.

#### Breakpoints:
- **Default Breakpoints**: `desktop`, `tablet`, `mobile`.
- **Optional Additional Breakpoints**: You can add custom breakpoints like `desktop-xl`, `desktop-xxl`, or `desktop-xxxl` based on project needs.

#### Types of Text Styles:
- **Title**: Represents headings.
- **Body**: Represents paragraphs.

---

## **Color Variables**

### **1. Creating and Editing Colors**
- **Location**: Use the **Swatches group** under the **Local Variables** section in the **Properties Panel** on the right-hand side of the Figma window.

### **2. Organizing Colors**
- Group colors based on their usage in the stylesheet:
  - **Background Colors**: For backgrounds.
  - **Text Colors**: For text elements.
  - **Border Colors**: For borders.
  - **Shadow Colors**: For shadows.
  
### **3. Naming Convention**
- **Simple and Dashed**: Use dashes for multi-word names.
- Examples:
  - Single Word: `maroon`
  - Double Words: `midnight-blue`
  - With Variation: `midnight-blue-light`
  - With Type: `midnight-blue-shadow`

---

## **Checklist for Designers**

1. **Typography Section**:
   - Ensure all typefaces are listed.
   - Create text styles for all headings (`title`) and paragraphs (`body`) for each breakpoint.
   - Double-check the naming conventions.

2. **Color Section**:
   - Ensure all project colors are added.
   - Group colors by usage (backgrounds, text, borders, shadows).
   - Double-check the naming conventions for clarity and consistency.

3. **Verify Completeness**:
   - Ensure all necessary styles and variables are defined.
   - Ensure that the stylesheet matches naming convention guidelines.


<br>
<br>

---


**Written by Druhin from Not Another™.**

*Last updated on 6th Dec 2024.*
