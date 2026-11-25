# Smart India Hackathon Workshop
# Date: 25.11.26
## Reference Number: 26015627
## Name: Mohamed Adhil A

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
We propose an AI-powered mobile application that helps consumers verify product information before purchasing packaged goods.

The user scans a product label or barcode using a smartphone camera. The system uses OCR and AI to extract and analyse important product information.

Main features:
- Scan product labels and barcodes.
- Check printed MRP against the selling price entered by the consumer.
- Identify missing or unclear mandatory label information.
- Check expiry or best-before dates.
- Store digital purchase receipts.
- Generate evidence-based consumer complaints.
- Provide multilingual consumer awareness support.
## Technical Approach
Component       	 Technology
Frontend	           Flutter
Backend	             Python, FastAPI
Database          	 Firebase / MySQL
AI and OCR	         Tesseract, OpenCV
Machine learning	   Scikit-learn
Barcode scanning	   M  L Kit
Notifications	       Firebase Cloud Messaging

Working process
1. Consumer opens the application.
2. Scans the product package.
3. OCR extracts MRP, product name, quantity and date information.
4. System checks the extracted information against applicable packaged-commodity requirements.
5. Consumer enters the actual selling price.
6. System identifies possible price violations or missing information.
7. Consumer can save the report and prepare a complaint with supporting evidence.
Unique approach: The platform combines product-label verification, price comparison and complaint-evidence preparation in one application.
## Feasibility and Viability
Technical feasibility: Smartphone cameras, OCR, barcode scanning and cloud databases are readily available technologies. A prototype can be developed using open-source tools.

Economic feasibility: The application can be developed with low-cost software tools and existing smartphones, without requiring expensive hardware.

Operational feasibility: Consumers need only a smartphone to scan products and access the verification features.

Challenges and solutions:
Challenge	Solution
Unclear product labels	Image enhancement and manual correction
OCR mistakes	Confidence score and user confirmation
Missing product database	Allow manual information entry
Different package formats	Train OCR on different label layouts
Incorrect complaint details	Require consumer confirmation before submission

Viability: The prototype can initially be tested in supermarkets, local shops and retail stores. It can later be expanded through partnerships with consumer organisations and relevant authorities.
## Impact and Benefits
Social benefits
- Improves consumer awareness.
- Helps people understand product-label information.
- Encourages informed purchasing decisions.
Economic benefits
- Helps identify possible overcharging.
- Helps consumers preserve purchase evidence.
- Supports transparency in retail transactions.
Consumer protection benefits
- Makes product information easier to understand.
- Helps identify missing mandatory declarations.
- Simplifies preparation of consumer complaints.
Target beneficiaries: General consumers, students, senior citizens, consumer organisations and regulatory authorities.
## Research and References
1. Ministry of Consumer Affairs – Legal Metrology (Packaged Commodities) Rules, 2011

Information about MRP, net quantity, manufacturer details and other mandatory declarations.
Official Legal Metrology reference2. National Consumer Helpline

Government platform for consumer grievance registration and tracking.
National Consumer Helpline3. Consumer Affairs – Consumer Handbook

Consumer awareness information about MRP and packaged product declarations.
Consumer Protection Handbook4. Government Consumer App

Existing government application for consumer complaints and grievance tracking.
Consumer App official website5. Consumer Protection Act, 2019
Consumer Protection Act information
 Share project proposal
