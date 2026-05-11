# Reflection

**Question:** How much data your publisher program will send to the message broker in one run?
> **Answer:**
> Since in `main.rs` on main function there are 5 data related to user created, then publisher will send 5 unit data to message broker in one run.

**Question:** The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
> **Answer:**
> This mean both subscriber and publisher interact the same message broker that way subscriber and publisher can communicate with each other.

# RabbitMQ Screen
![RabbitMQ Screen](images/RabbitMQ_Screen.png)
