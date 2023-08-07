# Content Security Policies (CSP) 
Magento cores whiltelist

Content Security Policies (CSP) are a powerful tool to mitigate against Cross Site Scripting (XSS) and related attacks, including card skimmers, session hijacking, clickjacking, and more. Web servers send CSPs in response HTTP headers (namely Content-Security-Policy and Content-Security-Policy-Report-Only) to browsers that whitelist the origins of scripts, styles, and other resources. Together, CSPs and built-in browser features help prevent:

Loading a malicious script from an attacker’s website
A malicious inline script from sending credit card info to an attacker’s website
Loading a malicious style that will make users click on an element that wasn’t supposed to be on a page
See Content Security Policy (CSP) and Content-Security-Policy to learn more about CSP and each individual policy.

For more detils refere to

https://devdocs.magento.com/guides/v2.3/extension-dev-guide/security/content-security-policies.html
