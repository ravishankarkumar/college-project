these softwares [cloakroomv.x] are produced in versions
with the specificaitons as follows:

version
  1) only small lockers were available
  2) small and large lockers were available
  3) small, medium and large lockers were available

  4) there was a bug in the previous systems.
     we were innocently releasing a lock if
     user was entring a PNR equivalent to lock-id
     generated by the system during the system initialization.
     i.e. we were over writing the status.
     so to overcome this bug a new version is released
     with a new error -5.

  5) the railway system demended a new software
     with the functionality of retiring rooms.
     So while keeping the old system intact, a
     new functionality to assign and release retiring rooms
     was also added.

     the way the system outputs the system image was also changed.