# Notes

## Modifying styles

- Inspect what you want to remove or modify
- Search for css class in codebase and remove
- Test removal or before removal modify in inspector to see if its
removal works

## Configuring the Shopping Cart

- Add SNIPCART_API_KEY environment variable
- Add `data-item-` keys for each product html element to make it a
Snipcart enabled buy button
  - data-item-id
  - data-item-price
  - data-item-image
  - data-item-name
  - data-item-url

## Setting Up a Custom Domain

- Follow instructions at Netlify to setup a CNAME