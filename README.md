# RaceCoin Core 0.2 (rebirth from 0.12.2)

<p align="center">
  <a href="https://www.racecurrency.com">Homepage</a> | <a href="http://explorer.racecurrency.com/">Block Explorer</a> | <a href="https://discord.gg/knxGVP">Discord</a> | <a href="https://twitter.com/RaceCryptoCoin">Twitter</a>
</p>

## About Race

RaceCoin (shortly: RACE) offers highly secured, anonymous transactions across the world. RACE supports Masternodes with a superb block reward. Features as Private Send and Instant Send make RACE a future-oriented currency on the market. RACE uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. RaceCoin Core is the name of the open source software which enables the use of this currency. RaceCoin Core is based on the [Dash](https://www.dash.org) codebase and is its own currency.

RaceCoin was taken over by a community of passionate volunteers after the original developers abandoned the project.

## Race Specifications

| Specification | Value |
| ------ | ------ |
| PoW Algorithm | Lyra2REv2 |
| Block Time Average | 90 seconds |
| Block Reward | 8 RACE |
| Block Reward Distribution | 40% to Masternodes, 60% to Miners initially, ramping up to 65% Masternodes, 35% miners |
| Masternode Collateral | 1000 RACE |
| Estimated Supply | 32.7 Mio. |
| Difficulty Retargeting | Every block |
| Difficulty Algorithm | Dark Gravity Wave v3 | 

## License

RaceCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

## Development Process

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/racecrypto/race/tags) are created to indicate new official,
stable release versions of RaceCoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

## Testing

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows
and Linux, OS X, and that unit and sanity tests are automatically run.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

### Important

RaceCoin is a project revived by the community. The takeover is still in progress, which means licencing information may not be fully correct at this moment. We do our best to update everything as soon as possible, and handle all tools we use according to the corresponding legal conditions.







