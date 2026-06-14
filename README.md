# Automation Report with Python
## Objectives
- Build an automated reporting solution that maps and reconciles data between Income Reports and Order Reports according to client requirements
- Reduce manual work and human error.
- Ensure accurate allocation of revenue, expenses, sold quantities, and refunded quantities at the item level.
- Improve reporting efficiency and support timely month-end closing and revenue booking.

## Background
- We need to accurately allocate the sold quantity, revenue, and expense amounts for each item within an order when preparing monthly reports for clients.
- Data sources from different e-commerce platforms are structured differently, but most provide two types of reports: Income Reports and Order Reports.
  ### Income report:
    - Provides Order IDs with accurate revenue and fee amounts.
    - Does not break down revenue and fees by individual items within an order.
    - Shows the total refunded quantity but does not indicate the refunded quantity for each item or the actual sold quantity.
  ### Order report:
    - Provides Order IDs and breaks them down by SKU (individual items within an order).
    - Shows sold quantities and refunded quantities by SKU.
    - However, the revenue and expense amounts are not always accurate, so we must rely on the Income Report for financial figures.
 
## Challenges
- We manage multiple brands under strict month-end closing timelines.- Some data is over 50k line and Excel can handle it well
- Financial amounts must be accurate for revenue recognition and client reporting.
- Some datasets contain more than 50,000 rows, making processing in Excel inefficient and prone to errors.

