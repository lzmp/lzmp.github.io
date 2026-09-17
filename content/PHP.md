---
tags:
  - Topic/Programming
Publish: false
---
# PHP

## Emails

On anything else other than Windows, PHP relies on the system `sendmail` to send emails.
## Snippets

### Quickly show errors

```php
ini_set('display_errors', 1);
ini_set('display_startup_errors', 1);
error_reporting(E_ALL);
```