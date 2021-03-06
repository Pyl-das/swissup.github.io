---
layout: default
title: Changelog
description: magento2 recaptcha module changelog
keywords: " magento2 recaptcha, recaptcha extension, changelog "
category: reCAPTCHA
---

# Changelog

### Version 1.3.0

> Feb 6, 2020

 -  Protect checkout with recaptcha.
 -  Config recaptcha look for any form with ["Design Exceptions"](../configuration/).

### Version 1.2.3

> Dec 6, 2019

 -  Remove 'jquery/ui' dependency to prevent message about slow performance in browser console at Magento 2.3.

### Version 1.2.2

> Jul 29, 2019

 -  Fixed error - No property exists by the name 'formId' in Magento 2.1.x.
 -  Slightly improve recaptcha styles for newsletter. Prevent recaptcha from streching newsletter form on small screens.

### Version 1.2.1

> Jun 12, 2019

 -  Fixed missing recaptcha at some pages for newsletter form. Forgot password page is one of them.
 -  Added comment to general section of Recaptcha settings at Magento Configuration.

### Version 1.2.0

> May 13, 2019

 -  New feature - protect "Subscribe to newsletter" with recaptcha.

### Version 1.1.3

> Mar 29, 2019

 -  Magento 2.3.1 compatibility (Fixed frontend js error)

### Version 1.1.2

> Dec 4th, 2018

 -  Updated google/recaptcha requirement to get latest stable version.
    (Magento 2.3.0 compatibility)

### Version 1.1.1

> Nov 8th, 2018

 -  Use curl to request recaptcha validation. It makes request slightly quicker.
 -  Improve module stability.

### Version 1.1.0

Internal module naming convention was updated. We applied this changes to reach full compatibility with Magento Marketplace policy.

### Version 1.0.1

 -  Add reCAPTCHA in authentication popup.
 -  Do not load JS ans CSS for default Magento Captcha when reCAPTCHA enabled.

### Version 1.0.0

Initial release.

Extension replaces default Magento Captcha with Google reCAPTCHA.
