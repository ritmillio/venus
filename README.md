# Venus - Shopify Theme with Tailwindcss and Fontawesome :rocket::rocket:

This repository is a starting point for developing Shopify Themes with Tailwindcss and Fontawesome

## Workflow

A short description of this workflow:

- Edit theme locally using the Shopify CLI

### Technologies used

- Tailwind CSS
  - The main css file is located in `css/styles.css`
  - Tailwind CDN is used for development therefor you do not need to compile every single class, please note that If you forgot to delete the cdn script your theme will suffer performance issues on prod.
  - You will find your compiled Tailwind file in `assets/styles.css.liquid`,
  - Purge is enabled, after you compile Tailwind, your `assets/styles.css.liquid` file will be ready on production
- Shopify CLI
- Fontawesome

Currently the theme is under going maintance but you can check performance with Google Lighthouse


## Getting started

### Prerequisites

- [Theme Kit](https://shopify.dev/themes/tools/theme-kit/getting-started)
- [Node.js](https://nodejs.org/)

### Installation

1. Download this theme as a zip, locate Online Store>Themes at your Shopify store and under Theme library you can upload your theme with the Add theme button 

2. Locate Apps and find `Manage private apps`, then Create new private app --> Give a private app name then in the Admin API select all the available checkboxes to Read and Write or if only Read is possible then select that choice. The last step is to Save the private app which will Generate an API password.