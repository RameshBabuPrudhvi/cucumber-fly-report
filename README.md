# Cucumber-live-report
Real-time reporting of cucumber tests

To start the services, one just need to type
```docker
docker-compose up -d
```
The -d is to start it in a detached mode, so that one can still use the terminal
The nice part is, to stop the services, we can use the same script, and just run the command below
```docker
docker-compose down 
```

That’s it, it will handle both stopping the services and pruning away the containers.
Hopes the above make it really simple to understand what Docker-Compose is. Cheers.

## Steps to view Cucumber Report:
- Open URL: http://localhost:5601
- Navigate to Stack Management under Management
- Click on Saved Objects under Kibana
- Click on import button
- Select  [export.ndjson](https://github.com/RameshBabuPrudhvi/cucumber-live-report/blob/main/export.ndjson)
- Click on Side menu and Expand Analytics
- Click on Dashboard
- Click on Cucumber Report

