### This is so wrong

    - 1
   - 2
  - 3
 - 4
- 5
 - 6
  - 7
   - 8
    - 9
     - 10

``$ for i in {1..20} ; do for ((j=1;j<i;j++)) ; do echo -n ' '; done; echo \* $i ; done; for i in {20..1} ; do for ((j=1;j<i;j++)) ; do echo -n ' '; done; echo \* $i ; done; ``


* 1
 * 2
  * 3
   * 4
    * 5
     * 6
      * 7
       * 8
        * 9
         * 10
          * 11
           * 12
            * 13
             * 14
              * 15
               * 16
                * 17
                 * 18
                  * 19
                   * 20
                   * 20
                  * 19
                 * 18
                * 17
               * 16
              * 15
             * 14
            * 13
           * 12
          * 11
         * 10
        * 9
       * 8
      * 7
     * 6
    * 5
   * 4
  * 3
 * 2
* 1



``$ for i in {1..20} ; do for ((j=1;j<i;j++)) ; do echo -n '  '; done; echo \* $i ; done; for i in {20..1} ; do for ((j=1;j<i;j++)) ; do echo -n '  '; done; echo \* $i ; done; ``
* 1
  * 2
    * 3
      * 4
        * 5
          * 6
            * 7
              * 8
                * 9
                  * 10
                    * 11
                      * 12
                        * 13
                          * 14
                            * 15
                              * 16
                                * 17
                                  * 18
                                    * 19
                                      * 20
                                      * 20
                                    * 19
                                  * 18
                                * 17
                              * 16
                            * 15
                          * 14
                        * 13
                      * 12
                    * 11
                  * 10
                * 9
              * 8
            * 7
          * 6
        * 5
      * 4
    * 3
  * 2
* 1


``$ for i in {1..20} ; do for ((j=1;j<i;j++)) ; do echo -n '   '; done; echo \* $i ; done; for i in {20..1} ; do for ((j=1;j<i;j++)) ; do echo -n '   '; done; echo \* $i ; done; ``
* 1
   * 2
      * 3
         * 4
            * 5
               * 6
                  * 7
                     * 8
                        * 9
                           * 10
                              * 11
                                 * 12
                                    * 13
                                       * 14
                                          * 15
                                             * 16
                                                * 17
                                                   * 18
                                                      * 19
                                                         * 20
                                                         * 20
                                                      * 19
                                                   * 18
                                                * 17
                                             * 16
                                          * 15
                                       * 14
                                    * 13
                                 * 12
                              * 11
                           * 10
                        * 9
                     * 8
                  * 7
               * 6
            * 5
         * 4
      * 3
   * 2
* 1



  - plop
  - x
  1. pl
  - plop
  - x 
  
Hello

  1. plop
  2. cdjnsk
  3. cdscds
  4. cds
  - cndjskcds
  - cdsnckjds
  - cdsncjkdsncds
  - c
