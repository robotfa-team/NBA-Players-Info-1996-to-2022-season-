# NBA Players Info (1996 to 2022 Season) API

## Overview
This API provides comprehensive data on NBA players from the 1996 to 2022 seasons. As a basketball enthusiast, I created this dataset by leveraging the NBA Stats API to merge my passion for the sport with analytics. The dataset is rich with demographic, biographical, and performance details, making it an excellent resource for basketball fans, analysts, and developers.

---

## Content
The dataset contains over two decades of data on players who have been part of NBA team rosters. It includes:
- **Demographic Information**: Age, height, weight, and place of birth.
- **Biographical Details**: Teams played for, draft year, and draft round.
- **Performance Stats**: Basic box score statistics like games played, average points, rebounds, assists, etc.

### Data Quality
The dataset initially contained 52 rows of missing data, which have been manually filled using information from Basketball Reference. To the best of my knowledge, there are no other data quality issues.

---

## Analysis Ideas
- **Player Trends**: Explore how age, height, and weight trends have evolved over time due to changes in game philosophy and player development strategies.
- **Global Influence**: Analyze the geographical diversity of the NBA and the impact of overseas talents.
- **Career Studies**: Conduct longitudinal studies on player career arcs.

---

## How to Access the API

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started

1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/nba-players-info-1996-to-2022-season) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "NBA Players Info API" and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s an example in cURL:
     ```bash
     curl -X GET "https://nba-players-info-1996-to-2022-season.p.rapidapi.com/list" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: nba-players-info-1996-to-2022-season.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. Player Details
Retrieve detailed demographic and biographical information about a player:
```bash
GET /list
```

---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

