# 📝 Chapter 3: Lists in HTML

## 🌐 English

### 📚 Overview

Lists are an essential part of HTML as they help organize information in a structured manner. HTML provides three types of lists: ordered lists, unordered lists, and definition lists.

### 🏧 Types of Lists in HTML

1. **Unordered List (`<ul>`)**
   - Displays items with bullet points.
   - Each item is enclosed in `<li>` (list item) tags.

   **Example:**
   ```html
   <ul>
       <li>Apple</li>
       <li>Banana</li>
       <li>Cherry</li>
   </ul>
   ```
   **Rendered Output:**
   - Apple
   - Banana
   - Cherry

2. **Ordered List (`<ol>`)**
   - Displays items with numbers or letters.
   - Each item is enclosed in `<li>` tags.

   **Example:**
   ```html
   <ol>
       <li>First item</li>
       <li>Second item</li>
       <li>Third item</li>
   </ol>
   ```
   **Rendered Output:**
   1. First item
   2. Second item
   3. Third item

3. **Definition List (`<dl>`, `<dt>`, `<dd>`)**
   - Used to define terms and their descriptions.
   - `<dt>` represents the term, and `<dd>` represents the description.

   **Example:**
   ```html
   <dl>
       <dt>HTML</dt>
       <dd>HyperText Markup Language</dd>
       <dt>CSS</dt>
       <dd>Cascading Style Sheets</dd>
   </dl>
   ```
   **Rendered Output:**
   **HTML**
   - HyperText Markup Language
   **CSS**
   - Cascading Style Sheets

### 📌 Nested Lists
Lists can be nested inside one another to create subcategories.

**Example:**
```html
<ul>
    <li>Fruits
        <ul>
            <li>Apple</li>
            <li>Banana</li>
        </ul>
    </li>
    <li>Vegetables
        <ul>
            <li>Carrot</li>
            <li>Spinach</li>
        </ul>
    </li>
</ul>
```

**Rendered Output:**
- Fruits
  - Apple
  - Banana
- Vegetables
  - Carrot
  - Spinach

### 📝 Assignments

1. **Create a Grocery List**
   - Use an unordered list (`<ul>`) to display grocery items.
2. **Make a Step-by-Step Guide**
   - Use an ordered list (`<ol>`) to explain how to prepare tea.
3. **Define Technical Terms**
   - Create a definition list (`<dl>`) with at least three technical terms.
4. **Nested Lists Example**
   - Create a nested list with categories and subcategories.
5. **Customizing Lists with CSS**
   - Style an unordered or ordered list using CSS.

## 🌍 اردو

### 📚 جائزہ

HTML میں لسٹوں کا استعمال معلومات کو ترتیب دینے کے لیے کیا جاتا ہے۔ HTML میں تین قسم کی لسٹیں ہوتی ہیں: غیرترتیب شدہ لسٹ، ترتیب شدہ لسٹ، اور تعریف کی لسٹ۔

### 🏧 HTML میں لسٹوں کی اقسام

1. **غیرترتیب شدہ لسٹ (`<ul>`)**
   - اشیاء کو بلٹ پوائنٹس کے ساتھ دکھاتی ہے۔
   - ہر آئٹم `<li>` ٹیگ میں شامل ہوتی ہے۔

   **مثال:**
   ```html
   <ul>
       <li>سیب</li>
       <li>کیلا</li>
       <li>چیری</li>
   </ul>
   ```
   **ظاہری شکل:**
   - سیب
   - کیلا
   - چیری

2. **ترتیب شدہ لسٹ (`<ol>`)**
   - اشیاء کو نمبروں یا حروف کے ساتھ دکھاتی ہے۔
   - ہر آئٹم `<li>` ٹیگ میں شامل ہوتی ہے۔

   **مثال:**
   ```html
   <ol>
       <li>پہلا آئٹم</li>
       <li>دوسرا آئٹم</li>
       <li>تیسرا آئٹم</li>
   </ol>
   ```
   **ظاہری شکل:**
   1. پہلا آئٹم
   2. دوسرا آئٹم
   3. تیسرا آئٹم

3. **تعریف کی لسٹ (`<dl>`, `<dt>`, `<dd>`)**
   - اصطلاحات اور ان کی وضاحت کے لیے استعمال کی جاتی ہے۔
   - `<dt>` اصطلاح جبکہ `<dd>` اس کی وضاحت ہوتی ہے۔

   **مثال:**
   ```html
   <dl>
       <dt>HTML</dt>
       <dd>HyperText Markup Language</dd>
       <dt>CSS</dt>
       <dd>Cascading Style Sheets</dd>
   </dl>
   ```
   **ظاہری شکل:**
   **HTML**
   - HyperText Markup Language
   **CSS**
   - Cascading Style Sheets

### 📌 نیسٹیڈ لسٹ

**مثال:**
```html
<ul>
    <li>پھل
        <ul>
            <li>سیب</li>
            <li>کیلا</li>
        </ul>
    </li>
    <li>سبزیاں
        <ul>
            <li>گاجر</li>
            <li> پالک</li>
        </ul>
    </li>
</ul>
```

**ظاہری شکل:**
- پھل
  - سیب
  - کیلا
- سبزیاں
  - گاجر
  - پالک

### 📝 اسائنمنٹس

1. **گروسری لسٹ بنائیں**
   - غیرترتیب شدہ لسٹ (`<ul>`) استعمال کریں۔
2. **مرحلہ وار گائڈ تیار کریں**
   - ترتیب شدہ لسٹ (`<ol>`) استعمال کریں۔
3. **تکنیکی اصطلاحات کی وضاحت کریں**
   - کم از کم تین اصطلاحات کی تعریف (`<dl>`) میں دیں۔
4. **نیسٹیڈ لسٹ کی مثال دیں**
   - مختلف کیٹیگریز کے ساتھ بنائیں۔
5. **CSS کے ذریعے لسٹ کو اسٹائل کریں**
   - کسی بھی لسٹ کو اسٹائل کریں۔

