# CampusKart Manual QA Testing Portfolio

**Tester:** Lateefat Ogunjimi  
**Product:** CampusKart (`campuskart.site`)  
**Execution date:** 17 September 2026  
**Testing focus:** Buyer and Seller mobile web experience

## Project Overview
This repository documents a manual QA test cycle performed on CampusKart, an e-commerce marketplace. The work combined scripted functional testing with exploratory, negative, boundary, refresh, browser-navigation, role-switching, and orientation checks.

The purpose of this portfolio project is to demonstrate practical QA skills: test planning, test-case execution, defect reporting, evidence collection, risk assessment, and clear communication of release-impacting findings.

## Execution Summary
| Metric | Result |
|---|---:|
| Test cases executed | 67 |
| Passed | 55 |
| Failed | 12 |
| Blocked | 0 |
| Negative / edge cases | 38 |
| Documented defects | 12 |

## Scope
Testing covered homepage/navigation, search and categories, product details, cart and wishlist, buyer authentication/profile/orders, seller dashboard/products/orders/wallet/messages/profile validation, Help/FAQ, Terms & Privacy, role switching, and portrait/landscape responsiveness.

### Out of scope / constrained
Live payments, wallet withdrawals, financial settlement, completed-order lifecycle, seller ratings, seller product publishing/moderation, and broad desktop/Android/cross-browser coverage were not fully exercised in this cycle because safe funded transactions, completed-order data, identity verification, administrative approval, or additional devices were unavailable.

## Testing Approach
- Manual functional testing
- Exploratory testing
- Negative and boundary testing
- UI/usability checks
- Refresh and state-persistence checks
- Browser Back navigation checks
- Buyer/seller role-switching checks
- Portrait and landscape responsive checks
- Chrome DevTools / network observation where applicable

## Selected Findings
- **BUG-002:** Clearing search did not restore the default catalogue.
- **BUG-004:** Cart displayed **Unknown Seller** for products with known sellers.
- **BUG-007:** Invalid buyer login returned to the login form without useful error feedback.
- **BUG-008:** Browser Back after logout opened a persistent 404 page.
- **BUG-011:** Refreshing the Privacy view reset the selected tab to Terms.

The full defect register, severity/priority assignments, reproduction steps, expected/actual results, and evidence references are in the comprehensive QA report and workbook.

## Repository Structure
```text
CampusKart_Manual_QA_Portfolio/
├── README.md
├── Documentation/
│   ├── CampusKart_Test_Plan.docx
│   ├── CampusKart_Defect_Log.docx
│   ├── CampusKart_Test_Summary_Report.docx
│   └── CampusKart_Comprehensive_QA_Report.docx
├── Test-Cases-and-Defects/
│   └── CampusKart_QA_Test_Cases_and_Bug_Report.xlsx
└── Evidence/
    ├── BUG-001-manifest-404.png
    ├── BUG-002-search-clear-state.png
    ├── ...
    └── POSITIVE-*.png
```

## Key QA Skills Demonstrated
Test design and execution • defect reporting • severity/priority classification • evidence traceability • exploratory testing • negative testing • responsive testing • authentication/session testing • e-commerce workflow testing • DevTools/network observation • test summary reporting

## Notes on Evidence
The Evidence folder contains a curated subset of screenshots supplied during the test cycle. Unrelated screenshots and screenshots that could unnecessarily expose personal/account information were not included in this public-portfolio package. Some documented defects rely on executed observations where a single still image was not available or sufficient.

---
*Portfolio project based on a real manual QA exercise performed on the available CampusKart test environment.*
