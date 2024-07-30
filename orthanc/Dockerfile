FROM jodogne/orthanc:latest
WORKDIR /root/
RUN wget -q http://lsb.orthanc-server.com/plugin-dicom-web/mainline/libOrthancDicomWeb.so && \
    mv ./libOrthancDicomWeb.so /usr/local/share/orthanc/plugins/
