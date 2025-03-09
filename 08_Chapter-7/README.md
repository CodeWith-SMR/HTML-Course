# 📝 Chapter 7: Forms in HTML

## 🌐 English

### 📚 Overview
Forms are essential in web development for collecting user input. HTML provides the `<form>` element, which contains various input fields like text boxes, checkboxes, radio buttons, dropdowns, and buttons.

### 🏗️ Basic Form Structure
```html
<form action="submit.php" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  <br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  <br>
  <button type="submit">Submit</button>
</form>
```
- **`action`**: Defines where to send the form data.
- **`method`**: Specifies HTTP method (`GET` or `POST`).
- **`label`**: Describes input fields for accessibility.
- **`input`**: Defines form fields like text, email, password, etc.
- **`button`**: Submits the form.

### 🔘 Common Input Fields
| Field Type | Example |
|------------|---------|
| Text | `<input type="text">` |
| Password | `<input type="password">` |
| Email | `<input type="email">` |
| Number | `<input type="number">` |
| Radio Button | `<input type="radio">` |
| Checkbox | `<input type="checkbox">` |
| File Upload | `<input type="file">` |
| Submit Button | `<input type="submit">` |

### 📜 Select Dropdown
```html
<label for="country">Select Country:</label>
<select id="country" name="country">
  <option value="usa">USA</option>
  <option value="uk">UK</option>
  <option value="pakistan">Pakistan</option>
</select>
```

### 📋 Text Area (Multi-line Input)
```html
<label for="message">Message:</label>
<textarea id="message" name="message" rows="4" cols="30"></textarea>
```

### 🛠️ Form Validation
```html
<input type="text" name="username" required minlength="3" maxlength="10">
```
- **`required`**: Makes field mandatory.
- **`minlength`** / **`maxlength`**: Sets length restrictions.

### 📝 Assignments
1. Create a basic form with a name, email, and submit button.
2. Add a password field with a minimum length of 6 characters.
3. Implement a dropdown menu with at least 5 options.
4. Create a form with checkboxes and radio buttons.
5. Use JavaScript to validate form fields before submission.

---

## 🌍 اردو

### 📚 تعارف
فارمز ویب ڈویلپمنٹ میں صارفین سے معلومات حاصل کرنے کے لیے استعمال ہوتے ہیں۔ HTML میں `<form>` ٹیگ کے ذریعے مختلف ان پٹ فیلڈز جیسے ٹیکسٹ باکس، چیک باکس، ریڈیو بٹن، ڈراپ ڈاؤن اور بٹن شامل کیے جا سکتے ہیں۔

### 🏗️ بنیادی فارم کی ساخت
```html
<form action="submit.php" method="post">
  <label for="name">نام:</label>
  <input type="text" id="name" name="name" required>
  <br>
  <label for="email">ای میل:</label>
  <input type="email" id="email" name="email" required>
  <br>
  <button type="submit">جمع کروائیں</button>
</form>
```
- **`action`**: فارم کے ڈیٹا کو کہاں بھیجنا ہے۔
- **`method`**: HTTP طریقہ کار (`GET` یا `POST`)۔
- **`label`**: ان پٹ فیلڈز کی وضاحت کے لیے۔
- **`input`**: فارم فیلڈز جیسے ٹیکسٹ، ای میل، پاس ورڈ وغیرہ۔
- **`button`**: فارم جمع کروانے کے لیے۔

### 🔘 عام ان پٹ فیلڈز
| فیلڈ کی قسم | مثال |
|------------|---------|
| ٹیکسٹ | `<input type="text">` |
| پاس ورڈ | `<input type="password">` |
| ای میل | `<input type="email">` |
| نمبر | `<input type="number">` |
| ریڈیو بٹن | `<input type="radio">` |
| چیک باکس | `<input type="checkbox">` |
| فائل اپلوڈ | `<input type="file">` |
| سبمٹ بٹن | `<input type="submit">` |

### 📜 ڈراپ ڈاؤن مینیو
```html
<label for="country">ملک منتخب کریں:</label>
<select id="country" name="country">
  <option value="usa">امریکہ</option>
  <option value="uk">برطانیہ</option>
  <option value="pakistan">پاکستان</option>
</select>
```

### 📋 ٹیکسٹ ایریا (ملٹی لائن ان پٹ)
```html
<label for="message">پیغام:</label>
<textarea id="message" name="message" rows="4" cols="30"></textarea>
```

### 🛠️ فارم ویلیڈیشن
```html
<input type="text" name="username" required minlength="3" maxlength="10">
```
- **`required`**: ضروری فیلڈ بناتا ہے۔
- **`minlength`** / **`maxlength`**: لمبائی کی حد مقرر کرتا ہے۔

### 📝 اسائنمنٹس
1. ایک بنیادی فارم بنائیں جس میں نام، ای میل اور سبمٹ بٹن ہو۔
2. پاس ورڈ فیلڈ شامل کریں جس کی کم از کم لمبائی 6 کریکٹر ہو۔
3. ایک ڈراپ ڈاؤن مینیو بنائیں جس میں کم از کم 5 آپشنز ہوں۔
4. چیک باکس اور ریڈیو بٹن کے ساتھ ایک فارم تیار کریں۔
5. فارم فیلڈز کو جمع کروانے سے پہلے جاوا اسکرپٹ کے ذریعے ویلیڈیٹ کریں۔