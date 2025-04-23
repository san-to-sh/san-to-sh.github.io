---
layout: page
title: "Image Test"
---

## Testing Different Image Methods

### Method 1: Direct HTML
<img src="images/IMG_4886.png" alt="Test Image 1" width="300">

### Method 2: Markdown with Jekyll
![Test Image 2]({{ site.baseurl }}/images/IMG_4886.png)

### Method 3: Absolute Path
<img src="/images/IMG_4886.png" alt="Test Image 3" width="300">

### Method 4: Relative Path from Root
<img src="./images/IMG_4886.png" alt="Test Image 4" width="300">

### Method 5: Using site.url
<img src="{{ site.url }}/images/IMG_4886.png" alt="Test Image 5" width="300"> 