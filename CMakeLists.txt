cmake_minimum_required (VERSION 3.0.2) # 3.0.2 подходит
project (pid-1 LANGUAGES)
install (PROGRAMS finit ro-boot small-finit DESTINATION sbin)
install (FILES asutils-init DESTINATION sbin)
install (PROGRAMS no-resume DESTINATION share/pid-1)
