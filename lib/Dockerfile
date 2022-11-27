FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/ssh69/kkjj /umbi/Raganork
WORKDIR /umbi/Raganork
ENV TZ=Asia/Kolkata
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
