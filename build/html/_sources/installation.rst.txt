Installation
============

Clone and build the latest code
-------------------------------

Clone the repository (master branch)::

  $ git clone --recursive https://gitlab.com/dalton/lsdalton.git


Build the code::

  $ ./setup [--help]
  $ cd build
  $ make [-j4]

Run the test set::

  $ ctest [-j4]


Contributing changes
--------------------

Fork https://gitlab.com/dalton/lsdalton, commit your changes, and file a merge request. 
Always use feature branches, never push to the master branch.

