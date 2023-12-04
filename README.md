# django-tailwinds
starter config for django + tailwinds + flowbite

## Install node pakages:
```bash
npm install
# or
pnpm install
```
## Start Tailwinds static output (Automatic):
- check the node js pakage manager in manage.py (default = pnpm), if your are using npm then replace 'pnpm' with 'npm'
- proceed to run server as normal
## Start Tailwinds static output (Manual):
```bash
npx tailwindcss -i ./static/src/input.css -o ./static/src/output.css --watch
# or
pnpm tailwindcss -i ./static/src/input.css -o ./static/src/output.css --watch
```
## Run server:
```
python manage.py runserver      
```
