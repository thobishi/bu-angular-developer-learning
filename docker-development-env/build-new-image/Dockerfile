FROM node:12

# install angular cli
RUN npm install -g @angular/cli

# change working directory
WORKDIR /app

# create an application
RUN ng new bu-ng --routing

# change working directory
WORKDIR /app/bu-ng

# expose the app port
EXPOSE "4200"

# container cmd
CMD ["ng", "serve", "--host", "0.0.0.0"]