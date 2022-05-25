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

Open URL: http://localhost:5601
