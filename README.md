What is DigiByte?
----------------

DigiByte is a rapidly growing open-source blockchain created in late 2013 and released in early 2014. After 6 years of forward thinking development, DigiByte has become one of the safest, fastest, longest and most decentralized UTXO blockchain in existence.

For more information, as well as an immediately useable, binary version of the DigiByte Core software, go to the [DigiByte website](https://digibyte.io).

DigiByte FAQ
-------------

For all technical specifications, have a look at the [DGBWiki](https://www.dgbwiki.com/index.php?title=DigiByte#DigiByte_Technical_Specifications).

[DigiByte Community Info Paper (White Paper)](https://digibyte.io/docs/infopaper.pdf)

[DigiByte Integration Guide](https://digibyte.io/docs/integrationguide.pdf)

Launch Date: January 10th, 2014

Blockchain Type: Public, Decentralized, UTXO based, Multi-Algorithm

Ticker Symbol: DGB

Genesis Block Hash: "USA Today: 10/Jan/2014, Target: Data stolen from up to 110M customers"

Max Total Supply: 21 Billion DigiBytes in 21 Years (2035)

Current Supply: 13,232,243,330 (June 2020)

Block Reward Reduction: 1% Monthly

Current Block Reward: 665.63DGB (June 2020)

Mining Algorithms: Five individual: SHA256, Scrypt, Odocrypt, Skein & Qubit

Block Interval: 15 Second Blocks (75 seconds per algo)

Algo Block Share: 20% Block Share Per Algo (5)

Difficulty Retarget: Every 1 Block, 5 Separate Difficulties, independent difficulty for each Mining Algo

SegWit Support: Yes. First major altcoin to successfully activate Segwit. (April 2017)

Hardforks: 6. DigiShield, MultiAlgo, MultiShield, DigiSpeed, DigiSync, & Odocrypt

Softforks: 4. CSV, NVersionBits, SegWit & ReserveAlgo

You can mine DigiByte on one of five separate mining algorithms. Each algo averages out to mine 20% of new blocks. This allows for much greater decentralization than other blockchains. [Explanation by Jared Tate](https://twitter.com/jaredctate/status/1254788307071852544) why an attacker would still be unable to hardfork the blockchain, making DigiByte much more secure against PoW attacks than other blockchains.

DigiShield Hardfork: Block 67,200, Feb. 28th, 2014

MultiAlgo Hardfork: Block 145k, Sep. 1st 2014

MultiShield Hardfork: Block 400k, Dec. 10th 2014

DigiSpeed Hardfork: Block 1,430,000 Dec. 4th 2015

DigiSync Hardfork: Block 4,394,880 Apr. 24th 2017

Odocrypt Hardfork: Block 9,112,320 July 22nd 2019

DigiByte vs Bitcoin
-------------------

Security: 5 DigiByte mining algorithms vs. 1 Bitcoin mining algorithm.
DigiByte mining is much more decentralized.
DigiByte mining algorithms can be changed out in the future to prevent centralization.

Speed: DigiByte transactions occur much faster than Bitcoin transactions.
1-2 second transaction notifications.
15 second DigiByte blocks vs. 10 minute Bitcoin blocks.
DigiByte has 6x block confirmations 1.5 minutes vs. 1 hour with Bitcoin.

Transaction Volume: DigiByte can handle many more transactions per second.
Bitcoin can only handle 7-27 transactions per second.
DigiByte currently can handle 1066+ transactions per second.
The 2015 DigiSpeed hardfork introduced changes that double the capacity of the network every two years.

Total Supply: More DigiBytes, lower price, more micro transactions, better price stability.
21 billion DigiBytes will be created over 21 years.
Only 21 million Bitcoin will be created over 140 years.
1000:1 ratio. 1000 DigiByte for every Bitcoin.

Flexibility: Ability to quickly add new features.
DigiByte can add new features & upgrades much quicker than Bitcoin.
Future DigiByte upgrades will push transaction limit to several hundred thousand per second.

Marketability & Usability: DigiByte is an easy brand to market to consumers.
DigiBytes are much cheaper to acquire.

## Donate

[Donate to the DigiByte Foundation](https://digibytefoundation.io/donate/)
<br>
[Donate to the DigiByte Awareness Team](https://dgbat.org/#donate)


We appreciate your support!

License
-------

DigiByte Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/digibyte/digibyte/tags) are created
regularly to indicate new official, stable release versions of DigiByte Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

