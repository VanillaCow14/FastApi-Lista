# FastApi-Lista
En esta ocasion usaremos esta herramienta para crear backend en python.

from fastapi import FastAPI
app = FastAPI()

@app.get("/nombres") 
async def obtener_nombres(): 
  return ["Flitito", "Amewing", "Bongli"]

if __name__ == "__main__": 
  import uvicorn 
  uvicorn.run(app, port=8000)

  Este es el codigo dado y asi es como se mira una vez ejecutamos el link.
  ![image](https://github.com/VanillaCow14/FastApi-Lista/assets/142856302/fe9f1450-1d85-4939-af7d-4cb79c6a0d06)

  Como podemos ver despues de agregar un /nombres al link del puerto local podemos ver la lista de nombres que tenemos definida en el codigo.

