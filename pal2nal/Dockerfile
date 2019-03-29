FROM gcc:8
MAINTAINER Evan R. Rees "erees@wisc.edu"

ADD http://www.bork.embl.de/pal2nal/distribution/pal2nal.v14.tar.gz /opt/
ADD http://abacus.gene.ucl.ac.uk/software/paml4.9i.tgz /opt/

RUN cd && cd /opt/ \
  && tar xf pal2nal.v14.tar.gz \
  && mv pal2nal.v14/pal2nal.pl /bin

RUN cd /opt/ \
  && tar xf paml4.9i.tgz \
  && cd paml4.9i/ \
  && rm bin/*.exe \
  && cd src \
  && make -f Makefile \
  && mv baseml basemlg codeml pamp evolver yn00 chi2 /bin
