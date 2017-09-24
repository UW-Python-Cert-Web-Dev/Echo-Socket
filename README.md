## Homework

Your homework assignment for this week is to take what you’ve learned here and build a simple “echo” server.

The server should automatically return to any client that connects exactly what it receives (it should echo all messages).

You will also write a Python script that, when run, will send a message to the server and receive the reply, printing it to stdout.

Finally, you’ll do all of this so that it can be tested.

### Your Task

In our class repository, there is a folder resources/session01.

Inside that folder, you should find:

* A file tasks.txt that contains these instructions
* A skeleton for your server in echo_server.py
* A skeleton for your client script in echo_client.py
* Some simple tests in tests.py
* Your task is to make the tests pass.

### Running the Tests

To run the tests, you’ll have to set the server running in one terminal:

```$ python echo_server.py```

Then, in a second terminal, you will execute the tests:

```$ python tests.py```

You should see output like this:

```[...]```

```FAILED (failures=2)```
