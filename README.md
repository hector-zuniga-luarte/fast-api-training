# fast-api-training
Curso de FastAPI con el código generado por Michael Kennedy de talkPython. Se muestra solo como evidencia de la ejecución del curso.

La versión más completa del sitio construido en el curso. Lo pueden adquirir aquí https://training.talkpython.fm/courses/getting-started-with-fastapi
Curso muy recomendable

Se muestra versión completa con API's, BD y manejo de async/await.

requirements.txt

fastapi==0.70.0
uvicorn==0.15.0
aiofiles
python-multipart

# This is now available on PyPI.org, so we'll be using that one going forward.
fastapi-chameleon==0.1.12

starlette==0.16.0
progressbar2
python-dateutil
passlib

# Post-recording updates:
# SQLAlchemy is out of beta for 1.4+:
SQLAlchemy==1.4.31

# SQLAlchemy started enforcing the underlying Python DB API was truly async
# We don't really get that with SQLite but when you switch something like Postgres
# It would "light up" with async. Since recording, SQLAlchemy throws and error
# if this would be the case. We need to explicitly switch to aiosqlite.
aiosqlite>=0.17.0
greenlet
