FROM node:14-alpine
WORKDIR D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\customer-services
COPY ["package.json", "package-lock.json", "./"]
RUN npm install 
COPY . .
EXPOSE 3001
RUN chown -R node D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\customer-services
USER node
CMD ["npm", "start"]

