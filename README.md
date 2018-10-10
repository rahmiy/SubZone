# SubZone

This program SubZone will find all subdomains for a domain/host you specify, and Dns records of all the 
Dns server's for that domain/host, including in the records can be found owner/sys-admin email,telephone,location,
servers,description of any sofwtare using tcp/udp like sic_tcp.(example) wich would mean they domain has a VoIp
with port info and such. The possibiltes are endless depending on how well the domain/host has configured there 
Dns server.

## Getting Started

To get started simply Fork the repository, open up console(cmd/powershell/terminal) cd into repository folder with 
the SubZone v*.py (* is for latest Version, eg.1.0/2.0 etc). Then once that is done type "python SubZone.py -h"
that will give you the options/arguments you need to specify to run file. Arguments are as follows - example of commands...
- python SubZone.py -d (domain) -o (output)
- python SubZone.py -d https://facebook.com -o facebook.txt
- python subZone.py -d https://zonetransfer.me -o zone.txt
Above is the command layout, and some examples. If you wish to see how good! my program is.. I highly reccomend trying the above
TWO arguments with SubZone to see what Subdomains/Dns records you will receive for facebook.com(very many subsdomains) and
zonetransfer.me(the kinda of dns records you could get)
- NOTE: You wont always get Subdomains and Dns records. Some domains dont have any subdomains and/or some Dns servers are configured
correct like in facebooks, no dns records.. but got the subdomains.
- 100%: You will get everything that can be got from the domain/host!

### Prerequisites

Python - You will need to have python installed and be using at least python 3+

Libraries/Imports - I will be adding a requirments.txt and code to check imports & versions
and install as necessary. At this momment in time you will need to make sure you have them installed and up too date & working.



### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Python]('https://www.python.org/) - Python Software Foundation

## Contributing

Please read [CONTRIBUTING.md] for details on our code of conduct, and the process for submitting pull requests.

## Versioning

Versioning will be in terms off v1/v2.2/v3 etc. Highest number in version/file is the most up too date version of software.

## Authors

* **Nathan Corbin** - *All the work* - [ncorbuk](https://github.com/ncorbuk)

## Acknowledgments

* I took inspiration from [UnaPibaGeek](https://github.com/UnaPibaGeek) and her ctfr code.(check her out, great stuff)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

