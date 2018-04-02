FROM codesimple/elm:0.18
MAINTAINER Roberto Nogueira <enogrob@gmail.com>

# Deploy Rails App.
WORKDIR /usr/src/app
ADD elm-package.json ./
RUN elm-package install -y
