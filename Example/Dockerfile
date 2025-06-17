FROM rocker/r-base:4.4.0

RUN mkdir settings

COPY install_libraries.R settings/

RUN Rscript /settings/install_libraries.R
