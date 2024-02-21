1.) How to run the application:

(p_venv_3.10.12) vikram@vikram-ubuntu:~/python_vir_env_3.10.12/p_venv_3.10.12/git/Fast_API/00_hello world$ uvicorn main:app --reload
INFO:     Will watch for changes in these directories: ['/home/vikram/python_vir_env_3.10.12/p_venv_3.10.12/git/Fast_API/00_hello world']
INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [11116] using StatReload
INFO:     Started server process [11118]
INFO:     Waiting for application startup.
INFO:     Application startup complete.

2.) How to view the app in webpage

http://127.0.0.1:8000/docs

Verify logs in console where app was started
INFO:     127.0.0.1:39770 - "GET / HTTP/1.1" 200 OK
INFO:     127.0.0.1:50948 - "GET /docs HTTP/1.1" 200 OK
INFO:     127.0.0.1:50948 - "GET /openapi.json HTTP/1.1" 200 OK
INFO:     127.0.0.1:48908 - "GET / HTTP/1.1" 200 OK
