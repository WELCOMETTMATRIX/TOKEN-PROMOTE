# TOKEN-PROMOTE

Blazzy CRO Token Promotion
Welcome to the Blazzy CRO Token Promotion platform!

Overview
This project is designed to promote new and existing tokens, specifically focusing on the CRO token from the Cronos blockchain by Crypto.com. Here, users can create promotional posts for tokens, providing all necessary information and optionally embedding live charts for an interactive experience.

Purpose
Promotion: Easily promote any token with comprehensive details.
Visibility: Enhance token visibility within the crypto community.
User Engagement: Provide a dynamic interface for users to interact with token data through live charts.

Features
Token Creation Form: A modal form where users can input token details including:
Token Name
Symbol
Network (e.g., Cronos, Ethereum)
Contract Address
Total and Circulating Supply
Project Description
URL for live chart iframe (from services like GeckoTerminal or Dextools)
Live Token Posts: Display all created tokens in a scrollable container for easy browsing. Each token post includes:
Basic token information
Project description
Creation date and creator type (Registered User or Guest)
An optional live chart iframe
User Authentication: Simple login system to differentiate between registered users and guests.
Professional UI: A dark-themed interface with neon accents for a cyberpunk, crypto-friendly vibe.

How to Use
Login (optional): Click the "WELCOME TO BLAZZY PROMO" button to log in as a registered user. This affects how you're identified as a creator of a token.
Promote Token:
Click the "Promote Token" button to open the modal for token creation.
Fill in all the details for the token. Use the correct passcode (BLZMEME) to publish.
Optionally, add a URL for a live chart from GeckoTerminal or Dextools.
View Tokens:
Scroll through the list of promoted tokens. Each card displays all entered information and, if available, includes a live chart.

Known Limitations
No Data Persistence: Tokens are stored in memory and will be lost upon page refresh. For production, implement server-side data storage or use local storage for persistence.
Performance: Large numbers of tokens might affect performance. Consider implementing pagination or lazy loading for better scalability.
Security: Basic client-side validation is in place, but server-side validation and security measures are necessary for production.

Future Enhancements
Token Search: Implement a search function to find tokens by name or symbol.
User Profiles: Allow users to have profiles, follow tokens, and manage their posted tokens.
Responsive Design: Further enhance responsiveness for different device sizes.
Security Enhancements: Add server-side validation, secure authentication, and protect against common web vulnerabilities.
