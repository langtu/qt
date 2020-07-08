FROM rabits/qt:5.15-desktop
ENV DEBIAN_FRONTEND noninteractive
RUN sudo apt-get update                   && \
    sudo apt-get install libpulse-dev -y  && \
    sudo apt-get install libssl-dev -y    && \
    sudo apt-get install libusb-1.0-0-dev -y && \
    sudo apt-get install libudev-dev -y