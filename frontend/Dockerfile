FROM node:20-alpine

WORKDIR /app

COPY package*.json .
RUN npm install

COPY . .

# vite дев-сервер, работает на 5173
# host 0.0.0.0 — чтобы было видно снаружи контейнера
CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]
