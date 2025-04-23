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

### Method 6: With Renamed Image
<img src="images/profile.png" alt="Test Image 6" width="300">

### Method 7: Absolute Path with Renamed Image
<img src="/images/profile.png" alt="Test Image 7" width="300">

### Method 8: Optimized JPEG
<img src="images/profile_optimized.jpg" alt="Test Image 8" width="300">

### Method 9: Absolute Path with Optimized JPEG
<img src="/images/profile_optimized.jpg" alt="Test Image 9" width="300"> 