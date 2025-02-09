# Alien Elections: Pizza Planet Voting Analysis 🍕👽

### 🚧 A work in progress! 🚧

A Python data analysis project examining voting patterns in Pizza Planet's democratic Pizza Party elections. Investigates 5 election cycles (2008-2024) with anonymized voter data and ballot outcomes.

## Key Features
- **10 unique demographic dimensions** including galactic district, pizza affiliation, and voting method
- **2 crucial ballot measures** analyzed: Pineapple Ban legislation and Crust Type Preference
- **250,000+ anonymized records** spanning 5 election cycles (4-year intervals)
- **Advanced analytics including:**
  - Voter turnout trends by district
  - Pizza party affiliation correlations
  - Demographic predictors of ballot measure outcomes
  - Voting method analysis (dine-in vs drive-thru)

## Data Dictionary

| Column Name | Type | Description |
|-------------|------|-------------|
| `voter_id` | int | Anonymous 7-digit identifier |
| `election_year` | int | 4-digit election year (2008-2024) |
| `age` | int | 2-digit voter age (20-99) |
| `gender` | text | Self-identified gender (M/F) |
| `district` | text | Pizza Planet sector (8 regions) |
| `income` | int | Annual income in Galactic Credits |
| `marital_status` | int | Marriage status (True/False) |
| `voting_method` | text | Dine-in or Drive-thru voting |
| `pizza_affiliation` | text | Political party: Vegetarian/Cheese-only/Meat-lovers |
| `pineapple_ban_vote` | int | Support for pineapple prohibition |
| `crust_preference` | int | Ballot choice: Deep Dish or Thin Crust |
