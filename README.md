# FastApi User Authentication

This is an authenticated API in python and FastApi. It uses tokents to authenticate users.

# Installing External Modules

Make sure you have Python and pip installed on your system before running these commands

```bash
pip install fastapi

pip install "uvicorn[standard]"

pip install python-multipart

pip install python-jose[cryptography]

pip install passlib[bcrypt]
```

## Running The Program

To run the API, execute the following command:

```bash
python -m uvicorn main:app 
```