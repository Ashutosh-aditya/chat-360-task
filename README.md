# Log Ingestor and Query Interface (SDE-1 and SDE Intern Assignment)

Developed a log ingestor system that can efficiently handle vast volumes of log data, and offer a simple interface for querying this data using full-text search or specific field filters.

Both the systems (the log ingestor and the query interface) has been built using flask , HTML , CSS & Javascript.

I am using firebase realtime database for storing the logs and provided the credendials for your use. If you want to use your own credendials then get the cred from firebase. [Visit firebase console](https://console.firebase.google.com/). Make sure you are creating project for web.
## Project Overview

![WhatsApp Image 2024-05-14 at 17 55 28_ae1f5e43](https://github.com/Ashutosh-aditya/chat-360-task/assets/78680582/85147d78-82cd-48d6-b42d-f41376abfffe)
![WhatsApp Image 2024-05-14 at 17 55 05_7b9c6914](https://github.com/Ashutosh-aditya/chat-360-task/assets/78680582/b46393ad-1e15-4771-a626-e8278300763f)
![WhatsApp Image 2024-05-14 at 17 54 11_d5d9f961](https://github.com/Ashutosh-aditya/chat-360-task/assets/78680582/86e7b114-2c99-4212-affc-11ea34684a82)



## Quick Start (Steps to Run this project)

Here are some steps to run this project:

1. Clone the project ( open new terminal on your VSCode) 

```
git clone https://github.com/Ashutosh-aditya/chat-360-task
```

2. Make Virtual Environment for this project (optional)

```
python -m venv venv
```

3. Start Virtual Environment (if setup virtual enviroment)

```
venv/Scripts/activate
```

4. Install dependencies

```
pip install -r requirements.txt
```

5. Run the project

```
python main.py
```

6. Open localhost in browser

```
http://localhost:3000/
```

7. To Populate the logs

```
http://localhost:3000/
```

8. To filter logs

```
http://localhost:3000/get_logs
```

8. To filter  Multiple logs

```
http://localhost:3000/multiple_log_query
```



