# Task 1: Project Definition

## Project Title
**ShopSphere** – An Online Retail and Inventory Management Web Application

## Problem Statement
Local retail customers frequently struggle to check product availability and compare prices without physically visiting multiple stores or messaging sellers on social media. At the same time, store staff track orders and stock levels manually using spreadsheets or paper logs, which leads to human error, overselling out-of-stock items, and delayed order fulfillment. Store managers have no accurate, real-time data on daily sales performance or low-inventory alerts, resulting in lost revenue and dissatisfied customers.

## Objectives
* **O1:** Enable a customer to search for a product, add it to their cart, and complete a checkout order in under 2 minutes.
* **O2:** Update product stock quantities automatically within 1 second of a confirmed order so that out-of-stock items cannot be purchased.
* **O3:** Allow store staff to add, edit, or update product listings and order statuses in under 1 minute per item.
* **O4:** Provide store managers with a real-time dashboard summarizing total orders, revenue, and low-stock items by category and date.

## Scope
* **In Scope:**
  1. Customer registration, login, and profile management
  2. Product catalog browsing, category filtering, and keyword search
  3. Shopping cart management (add, update quantity, remove items)
  4. Order checkout and order status tracking
  5. Staff/Admin product and inventory management (CRUD operations)
  6. Manager sales and inventory summary report
* **Out of Scope:**
  1. Native iOS and Android mobile applications
  2. Live third-party credit card or cryptocurrency payment gateway processing (simulated checkout only)
  3. Automated third-party courier/shipping GPS tracking integration
  4. Multi-vendor marketplace bidding or auction features

## Stakeholders
| Stakeholder | Role / Interest | What They Need from the System |
| :--- | :--- | :--- |
| **Customers (Shoppers)** | End users buying products | Fast product search, accurate stock status, clear pricing, and a simple checkout and order tracking process. |
| **Store Staff (Inventory Clerks)** | Operational staff managing catalog & orders | An easy interface to add/edit products, update stock counts, and change order statuses (e.g., Pending, Shipped, Delivered). |
| **Store Manager / Business Owner** | Decision-maker overseeing business performance | Accurate sales summaries, order volume metrics, and low-stock alerts to restock popular items on time. |
| **System Administrator / IT Staff** | Technical maintainers of the web application | Secure role-based access control, reliable uptime, maintainable code, and easy database backups. |
| **Payment & Financial Auditor** | Accounting / financial oversight | Accurate, unalterable records of order totals, timestamps, and customer invoices for bookkeeping. |
| **Data Protection / Privacy Officer** | Regulatory compliance | Assurance that customer personal data (names, emails, addresses, passwords) is encrypted, securely stored, and compliant with privacy regulations. |

## Feasibility Check
* **Useful (Does it contribute to objectives?):** Yes, it directly solves customer browsing friction and eliminates manual stock-tracking errors for store staff and managers.
* **Buildable (Can our team build it in the time we have?):** Yes, a standard web-based e-commerce system with simulated checkout is completely achievable by our student team within the semester schedule using standard web technologies.
* **Integration (Does it depend on anything we cannot access?):** No external paid APIs or restricted systems are required, as authentication, database storage, and simulated checkout are self-contained within our application.
