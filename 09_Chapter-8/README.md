# 🏷️ Chapter 8: Extra Markup in HTML

## 🌐 English

### 📚 Overview
HTML provides various elements beyond basic structure to enhance content semantics and improve document organization. These extra markup elements help define the meaning and structure of a webpage.

---

### 🔖 **1. HTML Comments**
Comments are used to add notes in the HTML code that do not appear in the browser.
```html
<!-- This is a comment -->
```
**Use Case:** Comments help developers understand code sections.

---

### 📌 **2. `div` and `span` Elements**
These are container elements used to group content for styling and scripting.
- **`div`**: A block-level container.
- **`span`**: An inline container.

#### Example:
```html
<div class="container">
  <h2>Section Title</h2>
  <p>This is a paragraph inside a div.</p>
</div>
<span style="color: red;">This is a highlighted word.</span>
```

---

### 📝 **3. Meta Information (`<meta>` Tag)**
The `<meta>` tag provides metadata about the document, such as character encoding, description, and author.
```html
<meta charset="UTF-8">
<meta name="description" content="A tutorial on HTML extra markup">
<meta name="author" content="CodeWithSMR">
```
**Use Case:** Improves SEO and page information.

---

### 📜 **4. Escape Characters & Entities**
Special characters in HTML need to be written using character entities.
```html
<p>Use &lt;strong&gt; for bold text.</p>
<p>Copyright &copy; 2025</p>
```
**Common Entities:**
- `<` → `&lt;` (Less than)
- `>` → `&gt;` (Greater than)
- `&` → `&amp;` (Ampersand)
- `©` → `&copy;` (Copyright)

---

### 🔖 **5. `iframe` (Inline Frames)**
An `<iframe>` is used to embed another webpage inside a page.
```html
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```
**Use Case:** Embedding maps, videos, or other web pages.

---

### 🎨 **6. HTML5 Semantic Elements**
Semantic elements provide meaningful structure to web pages.
Examples:
- `<header>` – Represents the top section of a page.
- `<nav>` – Contains navigation links.
- `<article>` – Represents a self-contained piece of content.
- `<section>` – Groups related content.

Example:
```html
<header>
  <h1>Welcome to My Website</h1>
</header>
<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
</nav>
```

---

### 📝 Assignments
1. Add a comment inside an HTML file.
2. Use `<div>` and `<span>` to create a styled content block.
3. Include meta tags for description and author.
4. Display an iframe embedding a YouTube video.
5. Use escape characters to display HTML code inside a paragraph.

---

## 🌍 اردو

### 📚 تعارف
HTML اضافی عناصر فراہم کرتا ہے جو مواد کی بہتر وضاحت اور ویب پیج کی ساخت میں مدد کرتے ہیں۔ یہ عناصر صفحے کے مطلب اور تنظیم کو بہتر بناتے ہیں۔

---

### 🔖 **1. HTML تبصرے**
تبصرے کوڈ میں نوٹس کے لیے استعمال کیے جاتے ہیں اور براؤزر میں نظر نہیں آتے۔
```html
<!-- یہ ایک تبصرہ ہے -->
```
**استعمال:** کوڈ کو بہتر سمجھنے کے لیے۔

---

### 📌 **2. `div` اور `span` عناصر**
یہ کنٹینر عناصر ہیں جو مواد کو گروپ کرنے کے لیے استعمال کیے جاتے ہیں۔
- **`div`**: بلاک سطح کا کنٹینر۔
- **`span`**: لائن کے اندر استعمال ہونے والا کنٹینر۔

#### مثال:
```html
<div class="container">
  <h2>سیکشن کا عنوان</h2>
  <p>یہ پیراگراف div کے اندر ہے۔</p>
</div>
<span style="color: red;">یہ ایک نمایاں لفظ ہے۔</span>
```

---

### 📝 **3. میٹا معلومات (`<meta>` ٹیگ)**
`<meta>` ٹیگ صفحے کی تفصیلات فراہم کرتا ہے جیسے کردار انکوڈنگ، تفصیل، اور مصنف۔
```html
<meta charset="UTF-8">
<meta name="description" content="HTML اضافی عناصر پر سبق">
<meta name="author" content="CodeWithSMR">
```
**استعمال:** SEO اور صفحے کی معلومات بہتر بنانے کے لیے۔

---

### 📜 **4. Escape کردار اور اینٹیٹیز**
HTML میں کچھ خاص حروف کو خصوصی اینٹیٹیز کے ساتھ لکھنا ضروری ہوتا ہے۔
```html
<p>&lt;strong&gt; کا استعمال بولڈ متن کے لیے کریں۔</p>
<p>کاپی رائٹ &copy; 2025</p>
```
**عام اینٹیٹیز:**
- `<` → `&lt;` (کم سے کم نشان)
- `>` → `&gt;` (زیادہ سے زیادہ نشان)
- `&` → `&amp;` (ایمپرسینڈ)
- `©` → `&copy;` (کاپی رائٹ)

---

### 🔖 **5. `iframe` (ان لائن فریمز)**
`<iframe>` ایک اور ویب پیج کو شامل کرنے کے لیے استعمال ہوتا ہے۔
```html
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```
**استعمال:** ویڈیوز، نقشے یا دیگر ویب صفحات کو ایمبیڈ کرنے کے لیے۔

---

### 🎨 **6. HTML5 سمیانٹک عناصر**
سمیانٹک عناصر صفحے کی معنویت کو بہتر بناتے ہیں۔
مثالیں:
- `<header>` – صفحے کے ابتدائی حصے کو ظاہر کرتا ہے۔
- `<nav>` – نیویگیشن لنکس پر مشتمل ہوتا ہے۔
- `<article>` – ایک مکمل مضمون کی نمائندگی کرتا ہے۔
- `<section>` – متعلقہ مواد کو گروپ کرتا ہے۔

مثال:
```html
<header>
  <h1>میرے ویب سائٹ میں خوش آمدید</h1>
</header>
<nav>
  <a href="#home">ہوم</a>
  <a href="#about">متعلق</a>
</nav>
```

---

### 📝 اسائنمنٹس
1. HTML فائل میں ایک تبصرہ شامل کریں۔
2. `<div>` اور `<span>` کا استعمال کر کے ایک اسٹائل شدہ مواد بنائیں۔
3. صفحے کے لیے میٹا ٹیگز شامل کریں۔
4. ایک YouTube ویڈیو کو `iframe` کے ذریعے ایمبیڈ کریں۔
5. ایک پیراگراف میں Escape کردار استعمال کر کے HTML کوڈ ظاہر کریں۔

