FROM node:14-alpine
WORKDIR D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\api-gateway
COPY ["package.json", "package-lock.json", "./"]
RUN npm install 
COPY . .
EXPOSE 3000
RUN chown -R node D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\api-gateway
USER node
CMD ["npm", "start"]

