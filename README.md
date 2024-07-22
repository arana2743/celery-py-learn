# Learn Python Celery


Celery key features:
- Asynchronous Task Execution
- Distributed Task Queue
- Task Scheduling and Periodic Tasks
- Result Handling
- Error Handling and Retry Mechanism
- Monitoring and Management

Python Celery Implementation can be done with:
- Flask, Pyramid, Bottle
- Standalone Python
- Data processing and analysis
- API development


General Flow
<pre>
       Django       -->      Redis       -->     Celery      -->       DB
(Message Provider)  --> (Message Broker) --> (Celery Worker) --> (Result Backend)
</pre>