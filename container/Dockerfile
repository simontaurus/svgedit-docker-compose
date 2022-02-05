FROM node:16

# Create app directory
WORKDIR /usr/src/app/svgedit

# install svgedit
RUN set -x; \
    git clone --depth 1 https://github.com/SVG-Edit/svgedit.git /usr/src/app/svgedit \
    && npm i

EXPOSE 8000

CMD [ "npm", "run", "start" ]
