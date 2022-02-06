# ArnoDB

[ArnoDB][arnodb] is scraping, analysing and serving platform for various independent timestamped data sources. ArnoDB consists of following modules:

a. User management
b. Scrapers
c. Database adaptors
d. Sequencer
e. Web Rest API
f. Server synchronizer

## Source

Jadda daa.

    docker build -t ftep-build ./buildImg/
    docker run -v $PWD:$PWD -w $PWD ftep-build gradle build buildDist --parallel

Note that some additional paths or environment variables may be required for
each build task.

## License

ArnoDB is **licensed** under the [GNU Lesser General Public License][LGPL]. The
terms of the license are as follows:
