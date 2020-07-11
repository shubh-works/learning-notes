bb# Markdown

## What is markdown?
Markdown is a lightweight markup language created by John Gruber in 2004. It was now become one of the world's most popular markup language. A good example of usage of markdown can be seen in README documents in Github repositories

Unlike WYSIWYG editors like Microsoft Word where the user will click on buttons to format the text, markdown relies on syntax in the file to determine formatting of text like adding # to mark a heading (# heading) or double asterisk before and after text to mark the text as bold (\*\*bold text\*\*). Although it might seem that adding the formatting syntax will make the document complex and unreadable, markdown is designed to be readable and unobtrusive.

## Why did I choose markdown?
There are a number of benefits in using markdown listed below:
1. **Flexibility**: Markdown can be used for everything. It can be used to create websites, documents, notes, books, presentations, email messages and technical documentation. **In my case, I am using markdown to create my learning notes which I am publishing on [shubhworks.com](shubhworks.com)**.
2. **Portability**: Markdown files can be opened in virtually any application. This is opposite to proprietary formats like Microsoft Word. **This is very important for my use as I don't need to rely on any particular application for rendering the documents on the website**.
3. **Platform Independent**: Markdown files can be created and used on any device. **This helps the website as the documents will work on all the devices with minimal setup**.
4. **Future Proof**: As markdown files require only text editors, they don't rely on the existence of any particular application **This is helpful in ensuring that the website can work for longer without any major changes**.

## Markdown Cheat sheet
 This is a quick overview of all the markdown syntax elements.
 
 ### Basic Syntax
 These are the elements outlined in John Gruber's original design document. All Markdown applications support these elements.

> In the following example, I have used HTML \<br/> to render multiple lines in the table

| Element | Markdown Syntax |
| ----------- | ----------- |
| Heading | # H1 <br/> ##H2 <br/> ##H3 |
| Bold | \*\*bold text\*\* |
| Italic | \_italic text\_ |
| Blockquote | \> blockquote text |
| Ordered list | 1. first item <br/> 2. second item <br/> 3. third item |
| Unordered list | - first item <br/> - second item <br/> - third item |
| Code | \`code\` |
| Horizontal rule | --- |
| Link | \[title\]\(https://wwww.website.com\) |
| Image | \!\[alt text\]\(image.png\) |

### Extended Syntax
These elements extend the basic syntax by adding additional elements and might not be covered by every markdown application.
| Element | Markdown Syntax |
| ------- | --------------- |
| Table | \| Syntax \| Description \| <br/> \| ------- \| ----------- \| <br/> \| cell 1 \| cell 2 \|  |
| Fenced code block | \`\`\` <br/> \{ <br/>"firstName": "sample name"<br/>\} <br/> \`\`\` |
| Footnote | Here's a sentence with a footnote. [^1] <br/> [^1]: This is the footnote |
| Heading ID | ### Sample Heading {#custom-id} |
| Definition List | term <br/> : definition |
| Strikethrough | \~\~earth is flat\~\~ |
| Task list | - [x] Task 1 <br/> - [ ] Task 2 |