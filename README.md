# Administrador de la flotilla de vehículos empresariales

## Link to System Requirements

You can find the system requirements/project tickets on our Jira board: [VecinoVigilante Jira Board](https://vecinosvigilantes.atlassian.net/jira/software/projects/VV/boards/2)

## For running on development:

- Recommended python version: 3.11

1. Create enviroment:

```bash
python -m venv env
```

2. Activate enviroment:

On Windows:

```bash
env\Scripts\activate
```

On Unix or MacOS:

```bash
source env/bin/activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the server

```bash
uvicorn app.main:app --reload
```

5. Check for API docs at:

http://127.0.0.1:8000/docs

