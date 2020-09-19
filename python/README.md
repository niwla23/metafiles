# {{name}}
{{description}} written in Python

## Configuration
* Copy the .env.example file to .env
* Change the variables to your needs

## Installation / Run
### Bare metal
 * Optionally create a virtual environment and activate it.
 * `pip3 install -r requirements.txt`
 * {{`python3 main.py` or `flask run`}}

### Docker
 * `sudo docker run -p 5000:5000 {{image_url}}`

### Docker-Compose
 * `sudo docker-compose up -d`

## Usage
```bash
$ {{title}} [{{param1}}]
{{output}}
```
