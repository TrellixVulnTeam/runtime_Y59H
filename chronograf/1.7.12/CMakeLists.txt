cmake_minimum_required(VERSION 3.0)

include(../../cmake/Me.cmake)
include(../../MeDownload.cmake)

me_project(chronograf-1.7.12 3RD INSTALL)

me_download(
    "https://dl.influxdata.com/chronograf/releases/chronograf-1.7.12_linux_amd64.tar.gz"
    "usr/bin/chronoctl"
    "usr/bin/chronograf"
)
