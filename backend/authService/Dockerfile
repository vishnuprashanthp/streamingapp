FROM node:20
ENV PORT=3001
ENV MONGO_URI="mongodb+srv://vishnuprashanthp:Admin123@cluster0.envlj.mongodb.net/streamingapp"  
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3001
CMD [ "node", "index.js"]