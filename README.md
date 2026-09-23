# Blind-Date-Detroit-project


Blind Match Detroit is a curated matchmaking project focused on connecting singles across Metro Detroit based on preferences, lifestyle, compatibility, and profile information.

This repository documents the data analysis, matching logic, and product insights from the first two matchmaking rounds.

## Project Goals

- Analyze participant demographics and dating preferences
- Evaluate matchmaking outcomes
- Compare Round 1 and Round 2
- Identify improvements for future matching rounds
- Use participant data and feedback to inform the Blind Match Detroit web app
- Demonstrate an end-to-end analytics and product development workflow

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Excel / Google Sheets

## Project Components

### 1. Data Cleaning
- Standardized participant responses
- Cleaned age preferences
- Standardized city and location data
- Cleaned religion, lifestyle, and contact preference fields
- Removed duplicate and incomplete responses

### 2. Matchmaking Algorithm
The matchmaking algorithm uses a combination of hard compatibility rules and weighted scoring.

Factors include:

- Mutual gender preferences
- Mutual age preferences
- Location
- Children preferences
- Smoking preferences
- Relationship goals
- Religion
- Politics
- Lifestyle
- Shared interests
- Ideal first date
- Contact preference
- Bio similarity using TF-IDF and cosine similarity

Participants could receive up to two matches.

### 3. Match Quality Assurance
Matches were manually reviewed before being released.

QA included:

- Age compatibility
- Gender preference compatibility
- Location
- Relationship goals
- Children preferences
- Smoking preferences
- Religion
- Duplicate matches
- Unmatched participants
- Manual overrides where appropriate

### 4. Email Automation
Python was used to generate and send personalized match introduction emails.

The workflow included:

- Personalized match profiles
- Preferred contact information
- Batch email sending
- Error handling
- Email logs
- Delivery testing

### 5. Exploratory Data Analysis
Planned analysis includes:

- Participant demographics
- Gender distribution
- Age distribution
- Geographic coverage
- Dating preferences
- Match rate
- Compatibility-score distribution
- Round 1 vs. Round 2 comparison
- Feedback and date conversion
- NLP analysis of bios and open-ended responses

## Data Privacy

This project uses real participant data.

No personally identifiable information, including names, emails, phone numbers, or social media handles, is included in this public repository.

Any public datasets used for analysis will be anonymized or aggregated.

## Future Development

Blind Match Detroit is transitioning from a manual Google Forms / email workflow to a dedicated web application.

Future development will include:

- Participant profiles
- Automated matchmaking
- Match acceptance / decline
- Admin QA tools
- Match feedback
- Bug reporting
- Notification system
- Improved privacy controls

## Status

Round 1: Complete  
Round 2: Complete  
Round 3: Planned web app launch
