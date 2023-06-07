# Start from the ubuntu image
FROM ubuntu:20.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy the curler.sh file from this location to /usr/src/app/ creating /usr/src/app/curler.sh
COPY curler.sh .


# Execute a command with '/bin/sh -c' prefix

RUN apt-get update
RUN apt-get -y install curl

# When running docker run the command will be ./curler.sh
CMD ./curler.sh
