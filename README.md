# Automated Betting on Tippkick.de

This application automatically bets for you on your tippkick-site.
It uses historical data of 50 years German Bundesliga combined with the quotes for the teams during runtime to predict the results.
The script will log in with your credentials, enter the predictions and log out.

## ENVs needed

|env-name|description|example|
|-----|-----|-----|
|NAME| The name of your tipp-group.|https://www.kicktipp.de/myname/tippuebersicht => NAME=myname|
|EMAIL|Your email for tippkick.| - |
|PASSWORD|Your password for tippkick.| - |

## For usage as container

Run it in a cronjob every 6hrs for special events/ high match frequency, else every 24hrs is enough.