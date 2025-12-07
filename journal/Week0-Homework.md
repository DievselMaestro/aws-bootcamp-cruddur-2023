# Befehl um Budget Bucket zu erstellen
```powershell
aws budgets create-budget \
    --account-id 633415687998 \
    --budget file://aws\json\budget.json \
    --notifications-with-subscribers "file://C:\aws-bootcamp-cruddur-2023\aws\json\budget-notifications-with-subscribers.json"
```

# Befehl um Cloud Watch zu erstellen
```powershell
aws cloudwatch put-metric-alarm --cli-input-json "file://C:\aws-bootcamp-cruddur-2023\aws\json\alarm-config.json"
```