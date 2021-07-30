---
tags: docs sprint
---

# Jupyter alt text guide

*This document is a draft!*

[Alt text](https://webaim.org/techniques/alttext/) is descriptive text for images and a foundational requirement for creating [accessible](https://en.wikipedia.org/wiki/Web_accessibility) content. Like other writing, it can be useful to have a guide as a starting place for people writing and reviewing alt text to make consistent descriptions and avoid common mistakes.

For Jupyter accessibility sprints, we've provided the following guidelines for writing in English.

## Checklist for alt text review

The alt text has
- [ ] Correct spelling and no typos
- [ ] Periods and commas where relevant
- [ ] No more than three short, complete sentences
- [ ] A logical way of fitting in the rest of the documentation
- [ ] Consistent text and/or descriptions for the same elements in different images
- [ ] Areas of JupyterLab named as described [here](https://jupyterlab.readthedocs.io/en/stable/developer/contributing.html#user-interface-naming-conventions)


## Writing alt text

### Types of alt text

Just as not all images are the same, not all alt text is the same. What types of alt text makes sense for an image depends on the images' content and context.

In terms of content, images can be 
- Decorative (do not add content)
- Functional (add content with a use, often interactive)
- Informative (adds or illustrates content)
- Complex (adds a large amount of content)
 
For guidance on determining an image's role and writing appropriate alt text, refer to the [W3's alt decision tree](https://www.w3.org/WAI/tutorials/images/decision-tree/).

In terms of context, alt text needs to fit into the content that surrounds it. It can be helpful to ask questions like
- Is the image demonstrating something described in the text preceeding it? 
- Is the image adding content that hasn't been mentioned previously? 
- Does the image have a caption? 
- Does the image match one used elsewhere on the documentation? 

### Formatting

Consistently formatting alt text helps its readability whether or not it is read by assistive technology.

#### Punctuation

Write alt text as complete sentences. This means it needs to include a complete thought that can be understood on its own.

Just like other complete sentences needs punctuation. Commas and periods are the most important to include for alt text.

#### Capitalization

Alt text uses [sentence case](https://en.wikipedia.org/wiki/Letter_case#Sentence_case).

#### Character count

These guidelines do not limit alt text to a specific character count even though some other guidelines do. 

It is still important to know that alt text should be brief and direct. If a short sentence or three does not cover all the information, refer to the links in **Types of alt text** for different types and methods of describing images.

### Content

#### Basics

Here are some simple alt text guidelines to start with:

- Avoid starting with "an image of" or similar phrases. There is already information there that tells people it is an image.
- Do use descriptions of an image type if it supports the content. For example, writing an image is a "screen shot" informs that the image is within an interface. "Illustration" or "animation" can be used similarly.
- Check your spelling. You can always write alt text somewhere with spellcheck and transfer it to your main workspace.
- Write with [plain language](https://www.plainlanguage.gov/guidelines/)
- Acronyms are the only things that need all-caps.
- Text in an image needs to be written as text somewhere else. If it is short, it can be in the alt text.

#### Color and directional words

Alt text can be used by people who are anywhere from blind to sighted. Colors and directions (like left or right) are visual-rooted descriptions. While they can be used, do so only when relevant to the context of the image.

Consider if
- The image is using colors with meaning, like color-coding
- The placement of an element contributes to it's relationship to other elements (in documentation, screen shots are often showing people where they need to navigate and this may be important)
- The colors or directions matter in the scope of the content as a whole

#### Images with people

Like all other alt text, context is key to deciding what to write. Writing about people, especially in cases where the people in the photo aren't known, takes care.

The most general guideline is to avoid making assumptions about the people in the photos. Make choices based information in the surrounding content or an external source if relevant.

If the people in a photo are known and it is relevant to the content, put their name in the alt text. Other descriptions aren't usually necessary once the name is used.

It is also best to 
- Use gender-neutral language
- Avoid describing physical features unless it is necessary for supporting the content
- Use general terms for a group of people rather than describing each individual

#### Documentation-specific

Documentation benefits from clear, consistent writing and only as much detail is needed to communicate the goal. Alt text is still writing and needs to fit within the goals of the documentation at large.

Things to consider:
- Use consistent language for the descriptions of elements, interactions, or other units referenced in doumentation. 
- Use the expected naming conventions used in other parts of the project. 
- Use language that directly matches the text that the image is supporting when relevant
- Make the specificity and focus of the description match the content of the surrounding documentation

## Other guidelines

Follow a project's commit message format when applicable.

## Project-specific resources

TBD by project

## Alt text resources

This list includes resources linked elsewhere in the guide for easy access.

## Other alt text guides

[Google](https://developers.google.com/style/images#alt-text)
[Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style/Accessibility/Alternative_text_for_images)
