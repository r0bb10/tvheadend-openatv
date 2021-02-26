# tvheadend-openatv

Configure arguments:
  --build=x86_64-linux --host=mipsel-oe-linux --target=mipsel-oe-linux --prefix=/usr --exec_prefix=/usr --bindir=/usr/bin --sbindir=/usr/sbin --libexecdir=/usr/libexec --datadir=/usr/share --sysconfdir=/etc --sharedstatedir=/com --localstatedir=/var --libdir=/usr/lib --includedir=/usr/include --oldincludedir=/usr/include --infodir=/usr/share/info --mandir=/usr/share/man --disable-silent-rules --disable-dependency-tracking --with-libtool-sysroot=/home/oe1/atv64/build-enviroment/builds/openatv/release/gb7356/tmp/work/mips32el-oe-linux/tvheadend/4.3+gitAUTOINC+52b255940f-r0/recipe-sysroot --arch=mipsel --disable-hdhomerun_static --disable-ffmpeg_static --disable-libav --enable-nls

Compiler:
  Using C compiler:                        mipsel-oe-linux-gcc  -mel -mabi=32 -mhard-float -march=mips32 --sysroot=/home/oe1/atv64/build-enviroment/builds/openatv/release/gb7356/tmp/work/mips32el-oe-linux/tvheadend/4.3+gitAUTOINC+52b255940f-r0/recipe-sysroot
  Using C flags:                            -Os -pipe -g -feliminate-unused-debug-types -fmacro-prefix-map=/home/oe1/atv64/build-enviroment/builds/openatv/release/gb7356/tmp/work/mips32el-oe-linux/tvheadend/4.3+gitAUTOINC+52b255940f-r0=/usr/src/debug/tvheadend/4.3+gitAUTOINC+52b255940f-r0                      -fdebug-prefix-map=/home/oe1/atv64/build-enviroment/builds/openatv/release/gb7356/tmp/work/mips32el-oe-linux/tvheadend/4.3+gitAUTOINC+52b255940f-r0=/usr/src/debug/tvheadend/4.3+gitAUTOINC+52b255940f-r0                      -fdebug-prefix-map=/home/oe1/atv64/build-enviroment/builds/openatv/release/gb7356/tmp/work/mips32el-oe-linux/tvheadend/4.3+gitAUTOINC+52b255940f-r0/recipe-sysroot=                      -fdebug-prefix-map=/home/oe1/atv64/build-enviroment/builds/openatv/release/gb7356/tmp/work/mips32el-oe-linux/tvheadend/4.3+gitAUTOINC+52b255940f-r0/recipe-sysroot-native= 
  Using LD flags:                          -Wl,-O1  -Wl,--as-needed -ldvbcsa
  Build for arch:                          mipsel

Binaries:
  Using PYTHON:                            python
  Using GZIP:                              gzip
  Using BZIP2:                             bzip2

Options:
  pie                                      yes
  ccdebug                                  no
  cardclient                               yes
  cwc                                      yes
  cccam                                    yes
  capmt                                    yes
  constcw                                  yes
  linuxdvb                                 yes
  satip_server                             yes
  satip_client                             yes
  hdhomerun_client                         no
  hdhomerun_static                         no
  iptv                                     yes
  tsfile                                   yes
  dvbscan                                  yes
  timeshift                                yes
  trace                                    yes
  avahi                                    yes
  zlib                                     yes
  libav                                    no
  ffmpeg_static                            no
  libx264                                  yes
  libx264_static                           yes
  libx265                                  yes
  libx265_static                           yes
  libvpx                                   yes
  libvpx_static                            yes
  libtheora                                yes
  libtheora_static                         yes
  libvorbis                                yes
  libvorbis_static                         yes
  libfdkaac                                no
  libfdkaac_static                         yes
  libopus                                  yes
  libopus_static                           yes
  nvenc                                    no
  vaapi                                    no
  mmal                                     no
  omx                                      no
  inotify                                  yes
  epoll                                    yes
  pcre                                     no
  pcre2                                    yes
  uriparser                                yes
  ccache                                   no
  tvhcsa                                   yes
  bundle                                   no
  pngquant                                 no
  kqueue                                   no
  dbus_1                                   yes
  android                                  no
  gtimer_check                             no
  slow_memoryinfo                          no
  libsystemd_daemon                        no
  pcloud_cache                             yes
  ddci                                     yes
  cclang_threadsan                         no
  gperftools                               no
  execinfo                                 yes
  W_unused_result                          yes
  f_stack_protector                        yes
  f_stack_protector_strong                 yes
  f_stack_check                            yes
  f_PIE                                    yes
  fdatasync                                yes
  getloadavg                               yes
  atomic32                                 yes
  atomic_time_t                            yes
  atomic_ptr                               yes
  bitops64                                 yes
  lockowner                                yes
  qsort_r                                  yes
  stime                                    yes
  gmtoff                                   yes
  recvmmsg                                 yes
  sendmmsg                                 yes
  ifnames                                  yes
  py_gzip                                  yes
  bin_pkg_config                           yes
  bin_xgettext                             yes
  bin_msgmerge                             yes
  bin_gzip                                 yes
  bin_bzip2                                yes
  ssl                                      yes
  linuxdvbapi                              yes
  linuxdvb_ca                              yes
  upnp                                     yes
  inotify_h                                yes
  inotify_init1                            yes
  dvbcsa                                   yes
  epoll_create1                            yes
  mpegts                                   yes
  mpegts_dvb                               yes

Packages:
  openssl                                  1.0.2r
  zlib                                     1.2.11
  libpcre2-8                               10.33
  liburiparser                             0.9.3
  avahi-client                             0.7
  dbus-1                                   1.12.16

Installation paths:
  Prefix:                                  /usr
  Binaries:                                /usr/bin
  Libraries:                               /usr/lib
  Data files:                              /usr/share
  Man pages:                               /usr/share/man


