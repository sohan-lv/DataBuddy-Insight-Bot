# DataBuddy Purchase Insight Bot

An interactive AI chatbot built using **Botpress** that analyzes purchase order data and answers business-focused questions like:

- Which purchase orders generated the most profit?
- Which vendors were the most valuable?
- What is the estimated profit per order?

## Project Overview

This bot was designed to help stakeholders quickly derive insights from procurement data without needing technical expertise.

The dataset contains:
- Purchase order details
- Vendor names
- Cost vs. catalog price
- Estimated profitability

**All answers are generated based on assumptions**: we estimate that all items were sold at catalog price.

## Technologies Used

- **HTML/CSS**: Frontend layout and styling
- **Botpress Cloud**: Trained AI agent using uploaded dataset
- **Cyberduck**: Used for internal server hosting
- **JavaScript**: Botpress webchat integration

## Example Questions to Ask the Bot

- "What is the most profitable purchase order?"
- "Which vendor had the highest estimated revenue?"
- "Show purchase orders sorted by profit."

## Hosting Instructions

This chatbot was hosted on an internal server via Cyberduck (SFTP). To host it elsewhere:

1. Use any web server or hosting platform (e.g., GitHub Pages, Netlify, Firebase).
2. Ensure your Botpress script link is accessible:
   ```html
   <script src="https://cdn.botpress.cloud/webchat/v3.0/inject.js" defer></script>
   <script src="https://files.bpcontent.cloud/2025/06/29/13/20250629131633-NJ833BZV.js" defer></script>
