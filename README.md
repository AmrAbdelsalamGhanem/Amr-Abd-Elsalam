# Hi, I'm Abssalam 👋  
### 🛍️ Shopify Wizard | 🔍 CRO Specialist | 🖥️ Coding Enthusiast  

Welcome to my GitHub! I specialize in crafting **high-performing Shopify stores**.  
Here, you'll find:
- Custom Shopify themes.
- Conversion rate optimization scripts.
- Guides to advanced Shopify features.

🌟 **Let’s build something awesome together!**  

# Shopify Product Variant Customization  

This repository contains a step-by-step guide and working code for customizing Shopify product variant selectors. The customization improves user experience and supports dynamic updates.

## Features:
- Custom product variant selector using Liquid, JavaScript, and CSS.
- Dynamic updates for product details (price, image, etc.).
- Optimized for CRO (Conversion Rate Optimization).

## File Structure:
- **assets/**: Contains styles and scripts for dynamic updates.
- **snippets/**: Reusable Liquid code for variant customization.
- **templates/**: A custom product template demonstrating the implementation.

## Preview:
![Preview](preview.png)

## Installation:
1. Upload the `assets` files to your Shopify store.
2. Add the `variant-selector.liquid` snippet to your theme.
3. Use the `product.custom.liquid` template for products you want to customize.

## Demo:
[Live Demo](https://github.com/Absalam/shopify-product-variant-customization/demo)

---

# 🌟 مرحبًا بكم في صفحتي على GitHub 🌟

مرحبًا، أنا **عبدالسلام**! مطور ويب ومهتم بالتجارة الإلكترونية. هنا ستجد مشاريعي وأعمالي في البرمجة.

---

## 🔧 المهارات:
- HTML | CSS | JavaScript | Shopify Liquid
- تحسين محركات البحث (SEO)
- تطوير واجهات المستخدم (UI/UX)

---

## 📂 المشاريع البارزة:
1. [**متجر إلكتروني مخصص**](https://github.com/your-repo) - متجر إلكتروني باستخدام Shopify.
2. [**تصميم واجهة مستخدم احترافية**](https://github.com/your-repo) - تصميم موقع باستخدام CSS وBootstrap.

---

## 📬 للتواصل:
- 📧 البريد الإلكتروني: amr.omar304@gmail.com
- 🌐 [LinkedIn](https://www.linkedin.com/in/amrabdelsalam87)

- # أهلاً وسهلاً! 👋

مرحبًا بكم في ملفي الشخصي. أنا عبدالسلام، أعمل كمطور ويب وأحب تقديم حلول إبداعية.

- 💻 متخصص في تطوير المتاجر الإلكترونية.
- 📈 أعمل على تحسين المتاجر لزيادة معدل التحويل.

---

### ⭐ إحصائيات GitHub:

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=AmrAbdelsalamGhanem&show_icons=true)

[![GitHub followers](https://img.shields.io/github/followers/AmrAbdelsalamGhanem?label=Followers&style=social)](https://github.com/AmrAbdelsalamGhanem)
[![GitHub stars](https://img.shields.io/github/stars/AmrAbdelsalamGhanem?label=Stars)](https://github.com/AmrAbdelsalamGhanem)

## Example Code:
### Variant Selector Snippet:
```liquid
<div id="variant-selector">
  {% for variant in product.variants %}
    <button 
      class="variant-button" 
      data-variant-id="{{ variant.id }}"
      onclick="updateVariant('{{ variant.id }}')">
      {{ variant.title }} - {{ variant.price | money }}
    </button>
  {% endfor %}
</div>

<script src="{{ 'custom-scripts.js' | asset_url }}"></script>
<link rel="stylesheet" href="{{ 'custom-styles.css' | asset_url }}">




