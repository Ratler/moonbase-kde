(
  source /etc/profile.d/qt4.rc

  sedit "s:/usr/local:/usr:" qmpdclient.pro &&
  qmake                                     &&
  default_make

) > $C_FIFO 2>&1
