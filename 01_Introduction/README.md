# HTML Introduction

## What is HTML?
HTML (HyperText Markup Language) is the standard markup language for creating web pages. It structures web content and consists of various elements that tell the browser how to display information.

### Key Features of HTML
- **HTML describes the structure of a web page**
- **HTML consists of a series of elements**
- **HTML elements label pieces of content**, such as headings, paragraphs, links, etc.
- **HTML elements tell the browser how to display content**

## A Simple HTML Document
Here is an example of a basic HTML document:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
</body>
</html>
```

### Example Explained
- `<!DOCTYPE html>` declares the document as an HTML5 document.
- `<html>` is the root element of an HTML page.
- `<head>` contains meta-information about the HTML page.
- `<title>` specifies a title for the HTML page (visible in the browser tab).
- `<body>` contains the visible content, including headings, paragraphs, images, links, etc.
- `<h1>` defines a large heading.
- `<p>` defines a paragraph.

## What is an HTML Element?
An HTML element consists of a **start tag, some content, and an end tag**:

```html
<tagname> Content goes here... </tagname>
```

### Example:
```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

| Start Tag | Element Content | End Tag |
|-----------|----------------|---------|
| `<h1>` | My First Heading | `</h1>` |
| `<p>` | My first paragraph. | `</p>` |
| `<br>` | none | none |

**Note:** Some HTML elements, like `<br>`, have no content and are called empty elements. They do not have an end tag.

## Web Browsers
A web browser (Chrome, Edge, Firefox, Safari) reads HTML documents and displays them correctly. Browsers do not show HTML tags but use them to render content appropriately.

## HTML Page Structure
Here is a visual representation of an HTML page structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>
</body>
</html>
```

---

# HTML کا تعارف

## HTML کیا ہے؟
HTML (HyperText Markup Language) ویب صفحات بنانے کے لیے استعمال ہونے والی معیاری مارک اپ لینگویج ہے۔ یہ ویب مواد کی ساخت کو بیان کرتی ہے اور مختلف عناصر پر مشتمل ہوتی ہے جو براؤزر کو مواد کو ظاہر کرنے کا طریقہ بتاتے ہیں۔

### HTML کی بنیادی خصوصیات
- **HTML ایک ویب صفحہ کی ساخت بیان کرتا ہے**
- **HTML مختلف عناصر پر مشتمل ہوتا ہے**
- **HTML عناصر مواد کے ٹکڑوں کو لیبل کرتے ہیں**، جیسے کہ سرخیاں، پیراگراف، لنکس، وغیرہ۔
- **HTML عناصر براؤزر کو مواد کو ظاہر کرنے کا طریقہ بتاتے ہیں**

## ایک سادہ HTML ڈاکومنٹ
یہاں ایک بنیادی HTML ڈاکومنٹ کی مثال دی گئی ہے:

```html
<!DOCTYPE html>
<html>
<head>
    <title>صفحہ کا عنوان</title>
</head>
<body>
    <h1>میری پہلی سرخی</h1>
    <p>میرا پہلا پیراگراف۔</p>
</body>
</html>
```

### مثال کی وضاحت
- `<!DOCTYPE html>` اعلان کرتا ہے کہ یہ HTML5 ڈاکومنٹ ہے۔
- `<html>` ایک HTML صفحے کا بنیادی عنصر ہے۔
- `<head>` HTML صفحے کے بارے میں میٹا معلومات پر مشتمل ہوتا ہے۔
- `<title>` HTML صفحے کے لیے ایک عنوان مخصوص کرتا ہے (جو براؤزر کے ٹائٹل بار یا ٹیب میں نظر آتا ہے)۔
- `<body>` مرئی مواد پر مشتمل ہوتا ہے، جیسے کہ سرخیاں، پیراگراف، تصاویر، لنکس، وغیرہ۔
- `<h1>` ایک بڑی سرخی کی وضاحت کرتا ہے۔
- `<p>` ایک پیراگراف کی وضاحت کرتا ہے۔

## HTML عنصر کیا ہے؟
HTML عنصر **ایک سٹارٹ ٹیگ، کچھ مواد، اور ایک اینڈ ٹیگ** پر مشتمل ہوتا ہے:

```html
<tagname> یہاں مواد آتا ہے... </tagname>
```

### مثال:
```html
<h1>میری پہلی سرخی</h1>
<p>میرا پہلا پیراگراف۔</p>
```

| سٹارٹ ٹیگ | عنصر کا مواد | اینڈ ٹیگ |
|-----------|-------------|---------|
| `<h1>` | میری پہلی سرخی | `</h1>` |
| `<p>` | میرا پہلا پیراگراف۔ | `</p>` |
| `<br>` | کوئی نہیں | کوئی نہیں |

**نوٹ:** کچھ HTML عناصر، جیسے کہ `<br>`، کا کوئی مواد نہیں ہوتا اور انہیں خالی عناصر کہا جاتا ہے۔ ان کا کوئی اختتامی ٹیگ نہیں ہوتا۔

## ویب براؤزرز
ویب براؤزر (Chrome, Edge, Firefox, Safari) HTML ڈاکومنٹس کو پڑھتے ہیں اور انہیں درست طریقے سے ظاہر کرتے ہیں۔ براؤزر HTML ٹیگز کو ظاہر نہیں کرتا بلکہ ان کا استعمال مواد کو مناسب انداز میں دکھانے کے لیے کرتا ہے۔

## HTML صفحے کی ساخت
یہاں HTML صفحے کی ایک بصری نمائندگی دی گئی ہے:

```html
<!DOCTYPE html>
<html>
<head>
    <title>صفحہ کا عنوان</title>
</head>
<body>
    <h1>یہ ایک سرخی ہے</h1>
    <p>یہ ایک پیراگراف ہے۔</p>
    <p>یہ ایک اور پیراگراف ہے۔</p>
</body>
</html>
```