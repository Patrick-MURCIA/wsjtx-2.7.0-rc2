# wsjtx-2.7.0-rc2
sudo apt-get install asciidoc automake libtool texinfo gfortran libhamlib-dev qtbase5-dev qtmultimedia5-dev qttools5-dev asciidoctor libqt5serialport5-dev qttools5-dev-tools libudev-dev xsltproc libboost-dev libboost-log-dev libboost-regex-dev wget https://github.com/Patrick-MURCIA/wsjtx-2.7.0-rc2.git/wsjtx-2.7.0-rc2.tgz
tar xvfz wsjtx-2.7.0-rc2.tgz
cd wsjtx-2.7.0
mkdir build
cd build
cmake ..
make
sudo make install
cd ../..
systemctl restart openwebrx
