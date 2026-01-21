# Shopify Theme Customizations

## Feature: Color-Linked Products (Separate Products) (Metafield Based)

This feature allows products of the same type but different colors—created as separate Shopify products—to be displayed together on the product page like color variants.

> This approach is commonly used when inventory, pricing, or SKUs need to be managed per color.

### How it works
- Products are linked using a product metafield
- Each product represents a different color
- Theme renders linked products as color swatches
- Clicking a swatch navigates to the selected product 

## Feature: Product Custom Text Badge

Displays custom text labels (e.g. Premium, Lightweight) on product cards to highlight key product attributes or marketing messages.

### How it works
- Badge text is managed via product metafields
- A reusable snippet is rendered inside the product-media component
- Supports multiple labels per product
- Labels appear consistently across collection pages, related products, and recommendations

### Customization Options
- Background color and text color are controlled via theme settings under the Product Card configuration
- Additional customization options can be easily added, such as:
  - Label position (top-left, top-right, bottom, etc.)
  - Font size and font weight
  - Spacing and border radius
  - Conditional display based on product type, collection, or availability

### Use cases
- Highlight premium or featured products
- Display product attributes (e.g. Lightweight, Eco-friendly)
- Support marketing and merchandising campaigns

> The implementation is intentionally modular to keep the theme lightweight and easy to maintain.


### Theme
- Horizon (Shopify)

### Live Preview
Preview: https://githubtask.myshopify.com/
Password: dev-1234

Product page: https://githubtask.myshopify.com/products/red-short-sleeve-t-shirt

### Notes
This repository contains ONLY custom sections, snippets, blocks, and assets created by me.

The custom block is designed to be integrated within the product information section (e.g., the main product details block) of the Horizon theme.  
A screenshot is included to show how the block is connected inside the theme editor.

Base theme files and proprietary Shopify assets are NOT included.

