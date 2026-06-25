# Day-15-Working-with-the-iframe-Elements 🖼️

After Day 14's SVG line break trauma 💀, Day 15 was a breath of fresh air. Today I learned how to embed entire webpages inside my own!

### **What I Learned Today**

#### **1. What Are Replaced Elements?**
Replaced elements are HTML tags where the browser "replaces" your code with something else.
**Think:** You write `<img>` but browser shows an actual picture.

**Examples I learned:**
| Element | What you write | What browser shows |
| --- | --- | --- |
| `<img>` | `<img src="cat.jpg">` | Actual cat photo |
| `<video>` | `<video src="...">` | Video player |
| `<iframe>` | `<iframe src="...">` | Whole other webpage |

Key lesson: You don’t control what’s inside them. The browser + external source does.

#### **2. What is an iframe?**
`iframe` = "inline frame". It’s literally a window/portal into another webpage, right inside your page.

**Analogy:** Like picture-in-picture on YouTube, but for websites.

Basic syntax:
```html
<iframe src="https://example.com" width="600" height="400"></iframe>
