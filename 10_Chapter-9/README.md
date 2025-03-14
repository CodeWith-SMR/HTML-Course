# 🎬 Chapter 9: Flash, Video & Audio in HTML

## 🌐 English

### 📚 Overview

Multimedia elements like video and audio enhance web pages by making content more engaging. HTML provides built-in tags to embed media files without requiring external plugins.

---

## 🎥 Embedding Videos in HTML

### 🔹 Using the `<video>` Tag

The `<video>` tag allows embedding video files directly into web pages.

```html
<video width="640" height="360" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

- **`controls`**: Adds play, pause, volume, and fullscreen options.
- **`autoplay`**: Starts the video automatically.
- **`loop`**: Repeats the video when it ends.
- **`poster`**: Defines a preview image before the video plays.

### 🎞️ Multiple Video Formats

Different browsers support different formats, so it’s best to include multiple formats:

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.ogg" type="video/ogg">
  <source src="video.webm" type="video/webm">
  Your browser does not support the video tag.
</video>
```

---

## 🎵 Embedding Audio in HTML

### 🔹 Using the `<audio>` Tag

The `<audio>` tag allows adding sound to web pages.

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```

- **`controls`**: Adds play, pause, and volume options.
- **`autoplay`**: Starts the audio automatically.
- **`loop`**: Repeats the audio when it ends.

### 🎶 Multiple Audio Formats

To support all browsers, provide multiple audio formats:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  <source src="audio.ogg" type="audio/ogg">
  Your browser does not support the audio tag.
</audio>
```

---

## 🖥️ Flash Content (Deprecated)

Adobe Flash was previously used for multimedia, but it is now obsolete. HTML5 provides better, safer, and faster alternatives with the `<video>` and `<audio>` tags.

```html
<object width="400" height="300" data="animation.swf"></object>
```

⚠️ **Warning:** Flash is no longer supported in modern browsers.

---

## 📝 Assignments

1. Embed a video using the `<video>` tag with `controls` enabled.
2. Add multiple video formats to support different browsers.
3. Embed an audio file using the `<audio>` tag with a fallback message.
4. Create a responsive video using CSS.
5. Explain why Flash is obsolete and list its alternatives.

---

## 🌍 اردو

### 📚 تعارف

ویب پیجز میں ملٹی میڈیا شامل کرنا مواد کو مزید دلکش بناتا ہے۔ HTML میں بلٹ ان ٹیگز موجود ہیں جو اضافی پلگ انز کے بغیر ویڈیوز اور آڈیوز شامل کرنے کی سہولت فراہم کرتے ہیں۔

---

## 🎥 HTML میں ویڈیوز شامل کرنا

### 🔹 `<video>` ٹیگ کا استعمال

ویب پیج پر ویڈیوز شامل کرنے کے لیے `<video>` ٹیگ استعمال ہوتا ہے۔

```html
<video width="640" height="360" controls>
  <source src="video.mp4" type="video/mp4">
  آپ کا براؤزر اس ویڈیو کو سپورٹ نہیں کرتا۔
</video>
```

- **`controls`**: پلے، پاز، والیم اور فل اسکرین آپشنز شامل کرتا ہے۔
- **`autoplay`**: ویڈیو خود بخود چلنا شروع ہو جائے گی۔
- **`loop`**: ویڈیو ختم ہونے پر دوبارہ چلے گی۔
- **`poster`**: ویڈیو کے چلنے سے پہلے ایک تصویر دکھاتا ہے۔

### 🎞️ مختلف ویڈیو فارمیٹس

مختلف براؤزرز مختلف فارمیٹس کو سپورٹ کرتے ہیں، لہٰذا ایک سے زیادہ فارمیٹس شامل کریں:

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.ogg" type="video/ogg">
  <source src="video.webm" type="video/webm">
  آپ کا براؤزر ویڈیو ٹیگ کو سپورٹ نہیں کرتا۔
</video>
```

---

## 🎵 HTML میں آڈیو شامل کرنا

### 🔹 `<audio>` ٹیگ کا استعمال

ویب پیج پر آڈیو فائلز شامل کرنے کے لیے `<audio>` ٹیگ استعمال کیا جاتا ہے۔

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  آپ کا براؤزر اس آڈیو کو سپورٹ نہیں کرتا۔
</audio>
```

- **`controls`**: پلے، پاز اور والیم آپشنز شامل کرتا ہے۔
- **`autoplay`**: آڈیو خود بخود چلنا شروع ہو جائے گا۔
- **`loop`**: آڈیو ختم ہونے پر دوبارہ چلے گا۔

### 🎶 مختلف آڈیو فارمیٹس

مختلف براؤزرز کو سپورٹ کرنے کے لیے ایک سے زیادہ فارمیٹس شامل کریں:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  <source src="audio.ogg" type="audio/ogg">
  آپ کا براؤزر آڈیو ٹیگ کو سپورٹ نہیں کرتا۔
</audio>
```

---

## 🖥️ فلیش مواد (متروک)

ماضی میں ایڈوب فلیش کو ملٹی میڈیا کے لیے استعمال کیا جاتا تھا، لیکن اب یہ متروک ہو چکا ہے۔ HTML5 کے `<video>` اور `<audio>` ٹیگز زیادہ محفوظ اور بہتر متبادل فراہم کرتے ہیں۔

```html
<object width="400" height="300" data="animation.swf"></object>
```

⚠️ **نوٹ:** جدید براؤزرز میں فلیش کی حمایت ختم ہو چکی ہے۔

---

## 📝 اسائنمنٹس

1. `<video>` ٹیگ استعمال کرتے ہوئے ایک ویڈیو شامل کر یں جس میں `controls` ہوں۔
2. مختلف ویڈیو فارمیٹس شامل کریں تاکہ مختلف براؤزرز اسے چلا سکیں۔
3. `<audio>` ٹیگ کے ساتھ ایک آڈیو فائل شامل کریں اور متبادل پیغام بھی دیں۔
4. CSS کا استعمال کرتے ہوئے ایک ریسپانسیو ویڈیو بنائیں۔
5. فلیش کے متروک ہونے کی وجوہات بیان کریں اور اس کے متبادل لکھیں۔

