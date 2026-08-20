# TODO: Replace with actual base image once tech stack is finalized
FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --omit=dev || true
COPY . .
CMD ["node", "src/index.js"]
