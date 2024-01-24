# Security Policy

## Reporting a Vulnerability
Do not disclose security vulnerabilities or any other security-related issues here, please email us instead:

az-digital-security@list.arizona.edu

> Please include as much of the information listed below as you can to help us understand and resolve the issue:

* The type of issue (e.g., buffer overflow, SQL injection, or cross-site scripting.)
* Full paths of source file(s) related to the issue.
* The location of the affected source code (tag/branch/commit or direct URL.)
* Any special configuration required to reproduce the issue.
* Step-by-step instructions to reproduce the issue.
* Proof of concept or exploit code (if possible).
* Impact of the issue, including how an attacker might exploit the issue.

- - - -

## Never store credentials or any other sensitive data in GitHub such as:
* API keys, 
* Database usernames/passwords, 
* And private keys in their GitHub repositories.
  
- - - -

## Always use MFA
Strong passwords aren’t secure enough anymore. Attackers have developed several tested methods of stealing credentials, giving them unauthorized access to private accounts.

For this reason, enabling Multi-Factor Authentication (MFA) for all your GitHub is critical.
> MFA should be enforced for every GitHub user in your organization.
>> To require MFA,  select Your Profile Photo → Your Organizations→ Settings → Security→Authentication Security. You can see all the details here.

- - - -

## Do not add GitHub applications unless they have been approved/tested by the repo admin team (Access Control Team) first
> Note: 
>> Before adding a GitHub application, it is important to review the application's credibility.
>> Audit the permissions that it requires and make sure that it is not granted more than necessary.
>> Check for security issues and negative comments before authoring a GitHub application to your GitHub organization.

- - - -

## Disable public repository creation
Ensure repositories remain private by disabling public access entirely. By disabling public access, you can help prevent the accidental creation of publicly accessible repositories, which can result in the exposure of sensitive information. 

- - - -

## Configure IP whitelisting (only available on GitHub Enterprise) 

- - - -

## Scan Github repositories regularly to detect and address vulnerabilities as soon as possible
> Note:
>> Automating code scanning and integrating it into your development process can help catch vulnerabilities early on and prevent security issues from becoming more serious down the line.
