# 🖼️ Chapter 5: Images in HTML

## 🌐 English

### 📚 Overview
Images enhance web pages by making them more visually appealing and informative. HTML uses the `<img>` tag to display images. The `src` attribute specifies the image source, while the `alt` attribute provides alternative text.

### 🖼️ Basic Image Syntax
```html
<img src="image.jpg" alt="Description of Image">
```
- **`src`**: Defines the image file location.
- **`alt`**: Provides alternative text if the image cannot be displayed (useful for accessibility and SEO).

### 🌍 Absolute vs. Relative Image Paths
1. **Absolute Path** (Full URL to an image):
   ```html
   <img src="https://www.example.com/image.jpg" alt="Example Image">
   ```
2. **Relative Path** (Local file within your website structure):
   ```html
   <img src="images/photo.jpg" alt="Photo">
   ```

### 📏 Controlling Image Size
Images can be resized using `width` and `height` attributes:
```html
<img src="image.jpg" width="300" height="200" alt="Resized Image">
```
However, using CSS is recommended for better control:
```css
img {
  width: 300px;
  height: auto;
}
```

### 📱 Responsive Images
For modern web design, images should be responsive:
```html
<img src="image.jpg" style="max-width: 100%; height: auto;" alt="Responsive Image">
```
Another method is using the `srcset` attribute for different screen sizes:
```html
<img src="small.jpg" srcset="medium.jpg 600w, large.jpg 1200w" alt="Adaptive Image">
```

### 🏞️ Image Formats
Different formats are used based on requirements:
- **JPEG (.jpg)** – Best for photos (lossy compression).
- **PNG (.png)** – Supports transparency (lossless compression).
- **GIF (.gif)** – Used for simple animations.
- **SVG (.svg)** – Scalable vector graphics (best for icons and logos).
- **WEBP (.webp)** – Modern format with better compression and quality.

### 📝 Assignments
1. Insert an image using a relative path.
2. Add an image with `alt` text for accessibility.
3. Create a responsive image using CSS.
4. Display images using different formats (JPEG, PNG, SVG).
5. Use the `srcset` attribute to provide different image sizes.

---

## 🌍 اردو

### 📚 تعارف
ویب صفحات میں تصویریں شامل کرنے کے لیے `<img>` ٹیگ استعمال کیا جاتا ہے۔ `src` ایٹریبیوٹ تصویر کا ماخذ ظاہر کرتا ہے، جبکہ `alt` ایٹریبیوٹ متبادل متن فراہم کرتا ہے، جو تصویر نہ لوڈ ہونے کی صورت میں نظر آتا ہے۔

### 🖼️ بنیادی تصویر کا سینٹیکس
```html
<img src="image.jpg" alt="تصویر کی وضاحت">
```
- **`src`**: تصویر کا پتہ بتاتا ہے۔
- **`alt`**: اگر تصویر نہ لوڈ ہو تو متن دکھاتا ہے، جو SEO اور معذور افراد کے لیے مفید ہے۔

### 🌍 مطلق اور نسبتی راستے
1. **مطلق راستہ** (مکمل URL):
   ```html
   <img src="https://www.example.com/image.jpg" alt="مثالی تصویر">
   ```
2. **نسبتی راستہ** (ویب سائٹ کے اندر):
   ```html
   <img src="images/photo.jpg" alt="تصویر">
   ```

### 📏 تصویر کا سائز کنٹرول کرنا
HTML یا CSS سے تصویر کا سائز کنٹرول کیا جا سکتا ہے:
```html
<img src="image.jpg" width="300" height="200" alt="سائز تبدیل شدہ تصویر">
```
یا بہتر طریقہ CSS کا استعمال ہے:
```css
img {
  width: 300px;
  height: auto;
}
```

### 📱 ریسپانسیو تصاویر
ویب ڈیزائن میں تصاویر کا ریسپانسیو ہونا ضروری ہے:
```html
<img src="image.jpg" style="max-width: 100%; height: auto;" alt="ریسپانسیو تصویر">
```
یا `srcset` کا استعمال:
```html
<img src="small.jpg" srcset="medium.jpg 600w, large.jpg 1200w" alt="ایڈاپٹیو تصویر">
```

### 🏞️ تصویر کے فارمیٹس
مختلف ضروریات کے مطابق مختلف فارمیٹس استعمال کیے جاتے ہیں:
- **JPEG (.jpg)** – فوٹوز کے لیے بہترین (lossy compression)
- **PNG (.png)** – ٹرانسپیرنسی کو سپورٹ کرتا ہے (lossless compression)
- **GIF (.gif)** – سادہ اینیمیشنز کے لیے
- **SVG (.svg)** – اسکیل ایبل ویکٹر گرافکس (لوگوز اور آئیکونز کے لیے)
- **WEBP (.webp)** – جدید اور زیادہ مؤثر فارمیٹ

### 📝 اسائنمنٹس
1. ایک تصویر نسبتی راستے سے شامل کریں۔
2. `alt` ٹیکسٹ کے ساتھ تصویر شامل کریں۔
3. CSS کے ذریعے ایک ریسپانسیو تصویر بنائیں۔
4. مختلف فارمیٹس (JPEG, PNG, SVG) میں تصاویر دکھائیں۔
5. `srcset` ایٹریبیوٹ کے ذریعے مختلف سکرین سائزز کے لیے امیج فراہم کریں۔

