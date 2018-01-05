FROM drackenov/jobtracker_client

RUN mkdir -p /asset
RUN yarn build 
VOLUME /asset
CMD cp -r ./build /asset
