
  prepare_install &&

  install -m755 $SOURCE_CACHE/$MODULE-$VERSION /usr/bin/$MODULE  &&

  echo "export KDE4_INSTALL_DIR=\"${MODULE_PREFIX}\"" >> $SOURCE_DIRECTORY/kde4.rc  &&
  echo export PATH=\"'${PATH}':${MODULE_PREFIX}/bin\" >> $SOURCE_DIRECTORY/kde4.rc  &&
  echo export PKG_CONFIG_PATH=\"'${PKG_CONFIG_PATH}':${MODULE_PREFIX}/lib/pkgconfig\" >> $SOURCE_DIRECTORY/kde4.rc &&

  install -m644 kde4.rc /etc/profile.d/
