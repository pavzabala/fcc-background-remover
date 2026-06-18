# fcc-background-remover
Simple web app using a background remover API.

Based on FreeCodeCamp's tutorial: [How to Go From Hello World to Building Real-World Applications](https://www.freecodecamp.org/news/how-to-go-from-hello-world-to-building-real-world-applications/)

## Commands
- run the backend server: `uvicorn api.main:app --reload`
- test backend server: `curl http://localhost:8000/health`
- perform server test w/ test photo: `curl -X POST -F "file=@test_photo.webp" http://localhost:8000/remove-bg --output result.png`