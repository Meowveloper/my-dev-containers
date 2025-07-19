
FROM node:24

# Install PureScript, Spago, and esbuild
RUN npm install -g purescript spago esbuild

# Set up a non-root user
RUN useradd -ms /bin/bash user
USER user
WORKDIR /home/user/project
