This repository includes a simple Python Flask web site, made for demonstration purposes only.

### Local development

This project has Dev Container support, so you can open it in Github Codespaces or local VS Code with the Dev Containers extension. 

Steps for running the server: 

1. (Optional) If you're unable to open the devcontainer, [create a Python virtual environment](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments) and activate that.

2. Install the requirements:

```shell
python3 -m pip install -r requirements.txt
```

3. Run the local server: (or use VS Code "Run" button and select "Run server")

```shell
python3 -m flask --debug run
```

3. Click 'http://127.0.0.1:5000' in the terminal, which should open the website in a new tab.

4. Try the index page, try '/hello?name=yourname', and try a non-existent path (to see 404 error).

