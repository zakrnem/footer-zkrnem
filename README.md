# footer-zkrnem

This module seamlessly integrates a standardized footer into Zakr Nem's projects, ensuring a consistent and professional touch across all pages.

## Installation and Usage

To include the styles of this module in your project, follow these steps:

1. Install the module using npm:

   ```bash
   npm install footer-zkrnem
   ```

2. In your project's index.js import the module's styles using the following line of code:

   ```javascript
   import '../node_modules/footer-zkrnem/styles.css'
   ```

3. In your DOM manipulation JavaScript file, you need to insert a specific function that will add the footer to your project's pages. This function is provided by the footer-zkrnem module.

To do this:

   ```javascript
   import { footer } from 'footer-zkrnem'
   footer()
```
This code imports the footer function from the footer-zkrnem module and then calls it. The function takes care of adding the standardized footer to your project.

4. That's it! The styles from the module will now be applied to your project.
