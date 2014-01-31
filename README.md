# ![aerofiles](img/logo.png)

**waypoint, task and tracklog file readers and writers for aviators**

[![Build Status](https://travis-ci.org/Turbo87/aerofiles.png?branch=master)](https://travis-ci.org/Turbo87/aerofiles)


## Features

* SeeYou CUP file reader (`aerofiles.seeyou`)
* WELT2000 file reader (`aerofiles.welt2000`)
* IGC file writer (`aerofiles.igc`)


## Development Environment

If you want to work on aerofiles you should install the necessary dependencies using:

    $ pip install -r requirements-test.txt

You can run the testsuite with:

    $ py.test

To run the whole testsuite you need to download some processable data like this:

    $ ./download_test_data.sh


## License

This code is published under the MIT license. See the [LICENSE](LICENSE) file for the full text.
