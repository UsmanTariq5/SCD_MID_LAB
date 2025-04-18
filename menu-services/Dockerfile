FROM node:14-alpine
WORKDIR D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\menu-services
COPY ["package.json", "package-lock.json", "./"]
RUN npm install 
COPY . .
EXPOSE 3004
RUN chown -R node D:\downloads\Lab_Sessional-main\Lab_Sessional-main\Cafe_Management_System\menu-services
USER node
CMD ["npm", "start"]

