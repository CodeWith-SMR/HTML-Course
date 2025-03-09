# 📊 Chapter 6: Tables in HTML

## 🌐 English

### 📚 Overview
Tables in HTML allow us to organize data in rows and columns. The `<table>` tag is used to create tables, and it contains various elements to structure the data effectively.

### 🏗️ Basic Table Structure
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
    <td>New York</td>
  </tr>
</table>
```
- **`<table>`**: Defines the table.
- **`<tr>`** (Table Row): Represents a row.
- **`<th>`** (Table Header): Represents header cells (bold & centered by default).
- **`<td>`** (Table Data): Represents regular data cells.

### 🎨 Styling Tables with CSS
```css
table {
  width: 100%;
  border-collapse: collapse;
}
th, td {
  border: 1px solid black;
  padding: 8px;
  text-align: left;
}
th {
  background-color: #f2f2f2;
}
```

### 🧩 Advanced Table Elements
#### 📌 Table Sections
```html
<table>
  <thead>
    <tr><th>Name</th><th>Age</th><th>City</th></tr>
  </thead>
  <tbody>
    <tr><td>Alice</td><td>30</td><td>London</td></tr>
  </tbody>
  <tfoot>
    <tr><td colspan="3">Total: 2 Entries</td></tr>
  </tfoot>
</table>
```
- **`<thead>`**: Defines the table header section.
- **`<tbody>`**: Contains the main data rows.
- **`<tfoot>`**: Represents the footer (summary rows).

#### 🔗 Merging Cells (Colspan & Rowspan)
```html
<table border="1">
  <tr>
    <th colspan="2">Full Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>28</td>
  </tr>
</table>
```
- **`colspan="2"`**: Merges two columns into one.
- **`rowspan="2"`**: Merges two rows into one.

### 📝 Assignments
1. Create a simple table displaying student names and grades.
2. Add a table header and footer to a table.
3. Style a table using CSS (borders, padding, and background colors).
4. Create a timetable using table cells.
5. Use `colspan` and `rowspan` to merge table cells.

---

## 🌍 اردو

### 📚 تعارف
HTML میں ٹیبلز ڈیٹا کو قطاروں اور کالموں میں ترتیب دینے کے لیے استعمال ہوتے ہیں۔ `<table>` ٹیگ سے ٹیبل بنایا جاتا ہے، جس میں مختلف عناصر ڈیٹا کو منظم کرتے ہیں۔

### 🏗️ بنیادی ٹیبل کا ڈھانچہ
```html
<table border="1">
  <tr>
    <th>نام</th>
    <th>عمر</th>
    <th>شہر</th>
  </tr>
  <tr>
    <td>علی</td>
    <td>25</td>
    <td>کراچی</td>
  </tr>
</table>
```
- **`<table>`**: ٹیبل کی وضاحت کرتا ہے۔
- **`<tr>`**: ٹیبل کی قطار بناتا ہے۔
- **`<th>`**: ٹیبل ہیڈر کے لیے استعمال ہوتا ہے (موٹا اور سینٹر میں ہوتا ہے)۔
- **`<td>`**: عام ڈیٹا کے لیے استعمال ہوتا ہے۔

### 🎨 CSS کے ساتھ ٹیبل کو خوبصورت بنائیں
```css
table {
  width: 100%;
  border-collapse: collapse;
}
th, td {
  border: 1px solid black;
  padding: 8px;
  text-align: left;
}
th {
  background-color: #f2f2f2;
}
```

### 🧩 جدید ٹیبل عناصر
#### 📌 ٹیبل کے مختلف حصے
```html
<table>
  <thead>
    <tr><th>نام</th><th>عمر</th><th>شہر</th></tr>
  </thead>
  <tbody>
    <tr><td>زین</td><td>30</td><td>لاہور</td></tr>
  </tbody>
  <tfoot>
    <tr><td colspan="3">کل اندراجات: 2</td></tr>
  </tfoot>
</table>
```
- **`<thead>`**: ہیڈر سیکشن
- **`<tbody>`**: مین ڈیٹا
- **`<tfoot>`**: خلاصہ / فوٹر

#### 🔗 سیلز کو ملانا (Colspan & Rowspan)
```html
<table border="1">
  <tr>
    <th colspan="2">پورا نام</th>
    <th>عمر</th>
  </tr>
  <tr>
    <td>علی</td>
    <td>حسن</td>
    <td>28</td>
  </tr>
</table>
```
- **`colspan="2"`**: دو کالم کو ایک میں ملاتا ہے۔
- **`rowspan="2"`**: دو قطاروں کو ایک میں ملاتا ہے۔

### 📝 اسائنمنٹس
1. ایک سادہ ٹیبل بنائیں جس میں طلباء کے نام اور گریڈز ہوں۔
2. ٹیبل کے لیے ہیڈر اور فوٹر شامل کریں۔
3. CSS کے ذریعے ٹیبل کو اسٹائل کریں۔
4. ایک شیڈول ٹیبل بنائیں جس میں مختلف سیشن ہوں۔
5. `colspan` اور `rowspan` کا استعمال کرتے ہوئے ٹیبل کے سیلز کو ضم کریں۔