FROM gcc:latest

COPY . /usr/src/cpp

WORKDIR /usr/src/cpp

RUN g++ -o main main.cpp

CMD [ "./main" ]