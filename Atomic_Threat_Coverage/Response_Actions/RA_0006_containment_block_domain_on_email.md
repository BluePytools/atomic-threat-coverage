| Title          | RA_0006_containment_block_domain_on_email                                                                                                      |
|:---------------|:-----------------------------------------------------------------------------------------------------------------|
| Stage    | containment                                                            |
| Automation | None |
| Author    | @atc_project                                                          |
| Creation Date    | 31.01.2019                                            |
| References     |<ul><li>[https://docs.microsoft.com/en-us/office365/securitycompliance/block-email-spam-to-prevent-false-negatives](https://docs.microsoft.com/en-us/office365/securitycompliance/block-email-spam-to-prevent-false-negatives)</li><li>[https://docs.microsoft.com/en-us/office365/securitycompliance/create-organization-wide-safe-sender-or-blocked-sender-lists-in-office-365](https://docs.microsoft.com/en-us/office365/securitycompliance/create-organization-wide-safe-sender-or-blocked-sender-lists-in-office-365)</li></ul>                                  |
| Description    | Block phishing attack origin on Email level.                                                               |
| Linked Response Actions | None |
| Linked Analytics |<ul><li>MS_email_server</li></ul> |


### Workflow

Block malicious sender (or entire domain, if possible) on Email Server using native filtering functionality.
