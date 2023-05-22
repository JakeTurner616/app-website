---
layout: default
---

<script async>
  var userAgent = navigator.userAgent || navigator.vendor || window.opera;
  
  if (/android/i.test(userAgent)) {
    // Android
    document.getElementById("appLink").href = "https://play.google.com/store/apps/details?id=org.serverboi.RealArtAI";
  } else if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {
    // iOS
    document.getElementById("appLink").href = "https://apps.apple.com/us/app/real-art-ai/id6449267914";
  } else {
    // Default to iOS link
    document.getElementById("appLink").href = "https://apps.apple.com/us/app/real-art-ai/id6449267914";
  }
</script>

<p align="center">
  <img src="https://raw.githubusercontent.com/JakeTurner616/JakeTurner616.github.io/main/assets/img/banner.png" alt="banner"/>
</p>

# Real Art AI

## Description
<p>The <a id="appLink" href="#">Real art AI</a> app allows users to easily create stunning digital art. Using cutting-edge AI users can create personalized illustrations, or upload photos and transform them into completely unique digital art pieces. Real Art AI gives anybody the tools to pull off advanced AI art techniques such as face-morphing, face-swap, background-swap/replace, up-scaling, and image beautification all in one place.</p>

## Features

- Txt2img

  The "Txt2img" tool works by utilizing an algorithm that has been trained on a dataset of images and their corresponding textual descriptions. This allows an AI model to understand the complex relationships between text and images, and to generate new images that accurately reflect a given text prompt.

- Img2img

  The "Img2img" tool utilizes an advanced deep learning algorithm that has been trained on a vast dataset of images. This allows the AI model to understand the complex relationships between different images and to generate new images that accurately reflect a given prompt. 

- Upscale

  Upscaling is a technique used to increase the resolution and improve the quality of an image or video. It works by analyzing the existing pixels in the image or video and using advanced algorithms to create new pixels that fill in the gaps between the existing ones. 

- Denoising strength

  The denoising strength parameter in img2img is an essential tool that enables users to balance the trade-off between noise reduction and the preservation of image details. By adjusting the denoising strength parameter, users can customize the amount of noise reduction applied to the image, ensuring that the final output meets their specific needs and preferences.

- Prompt autocomplete

  The prompt autocomplete feature works by using a GPT-2 like language model that has been trained on a dataset of txt2img prompts. When a user enters a partial description of an image, the model uses its training to generate a complete description that is consistent with the language patterns it has learned. This can save the user time and effort by generating a complete prompt without requiring them to manually enter all the details.

## Cross platform support
Real Art AI supports both [IOS](https://apps.apple.com/us/app/real-art-ai/id6449267914) and [Android](https://play.google.com/store/apps/details?id=org.serverboi.RealArtAI) phones!
