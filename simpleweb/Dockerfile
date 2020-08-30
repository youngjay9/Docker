# specify base image
FROM node:alpine

# install some dependencies
# 複製 simpleweb 底下的檔案至 container, 讓下方 npm install 執行時可以讀取 package.json
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]