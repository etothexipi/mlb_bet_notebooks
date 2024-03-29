# mlb_bet_notebooks
Jupyter notebooks running on AWS EC2 Amazon Linux 2 with s3 storage.

- Download gamelogs to get list of all team matchups and results. Use as input for scraping URLs.
- Scrape major league baseball stats from statfox.com at individual, matchup game level.
- Clean scrapes and build features, targets, weights, and betting odds.
- Build Random Forest model to predict winner and looser of future games given pre-game matchup stats. Use potential payouts/losses as weights in model training.

### Outcome
- Was never able to outperform the official betting odds prediction but came near ROC AUC of official odds. This is equivalent to almost breaking even if betting in real life (assuming $1 bet per match).
