docker build -t fftc .

docker run -it -v "$PWD":/usr/src/app fftc
