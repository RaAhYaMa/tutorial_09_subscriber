### What is amqp?
The connection string `guest:guest@localhost:5672` is used to connect to an AMQP server.

---

### What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
* first `guest`: The username for authentication.
* second `guest`: The password for authentication.
* `localhost`: The hostname or IP address of the AMQP server.
* `5672`: The port number that the AMQP server is listening on.

---

### Why the total number of queue is 22?

Because there's a delay in the code for about 1 second after quickly ran `cargo run` 5 times in publisher directory

![RabbitMQ Management](static/img/Screenshot%202025-05-13%20at%2013-41-03%20RabbitMQ%20Management.png)