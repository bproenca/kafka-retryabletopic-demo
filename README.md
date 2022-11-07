# kafka-retryabletopic-demo
Kafka non-blocking implementation to handle failed messages

This article is a demo for my tutorial on medium.com:

https://betterprogramming.pub/spring-boot-kafka-non-blocking-retries-a-hands-on-tutorial-a0c425acc3dd

### How to start the project

1. Go to src/main/resources
2. Run docker-compose up
3. Start the main app.
4. Send a GET HTTP request with a test message to the http://localhost:8090/produce/ endpoint.
