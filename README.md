# fcc-background-remover
Simple web app using a background remover API.

Based on FreeCodeCamp's tutorial: [How to Go From Hello World to Building Real-World Applications](https://www.freecodecamp.org/news/how-to-go-from-hello-world-to-building-real-world-applications/)
Additional backend logic added (CORS, fastapi Response) to allow full functionality.

## Commands
- run the backend server: `uvicorn api.main:app --reload`
- test backend server: `curl http://localhost:8000/health`
- perform server test w/ test photo: `curl -X POST -F "file=@test_photo.webp" http://localhost:8000/remove-bg --output result.png`

## Rembg Model
u2net.onnx model downloaded from: [danielgatis's github](https://github.com/danielgatis/rembg/releases/download/v0.0.0/u2net.onnx)