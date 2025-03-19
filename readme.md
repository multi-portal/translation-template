# MultiPortal Translation Project

## Overview
Welcome to the MultiPortal Translation Project! Our goal is to make MultiPortal accessible to a broader audience by allowing the community to contribute translations. The translation files are broken down into logical sections, and as the project progresses, we will continue refining them to enhance usability.

## File Structure
Each translation file follows a structured PHP array format. The structure of each file is as follows:

```php

return [
    'API TOKEN' => '',
    'An error occurred while processing the command.' => '',
    'Console Dashboard' => '',
];
```

### Translation Process
- Each array element represents a key-value pair, where the key is the original English text, and the value is the translated text.
- If the value is left empty (`''`), the message is considered untranslated.
- Messages no longer needed will have their translations enclosed between a pair of `@@` marks.
- Some messages use placeholders like `{action}`—these should remain unchanged in your translation.

## How to Contribute
1. **Download the Translation Files**
   - Clone the repository or download the necessary translation files.
   - The current structure of translation files is as follows:

```
    backups.php
    catalogue.php
    common.php
    config.php
    console.php
    dashboard.php
    datacenter.php
    errors.php
    iso.php
    license.php
    logs.php
    menu.php
    networking.php
    settings.php
    update.php
    user.php
    virtualdatacenter.php
    virtualmachines.php
```

2. **Translate the Files**
   - Each PHP file contains an array of text strings used in MultiPortal.
   - Replace the English text with your translated version while keeping the array keys unchanged.

3. **Submit Your Translations**
   - Once you've translated a file, submit it back to us for review.
   - You can send your translated files via a pull request (if using a repository) or email them to us.
   
4. **Review and Implementation**
   - We will review submitted translations for accuracy and consistency.
   - Once approved, your translations will be merged into the MultiPortal project.

## Guidelines for Translators
- **Keep the formatting intact** – Ensure that keys and array structures remain unchanged.
- **Report any missing or unclear text** – If something is unclear or missing, let us know!

## Contact
For any questions or clarifications, reach out to us via our official communication channels.

Thank you for contributing to the MultiPortal Translation Project!

