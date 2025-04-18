FROM node:14-alpine
WORKDIR D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\inventory-services
COPY ["package.json", "package-lock.json", "./"]
RUN npm install 
COPY . .
EXPOSE 3002
RUN chown -R node D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\inventory-services
USER node
CMD ["npm", "start"]

