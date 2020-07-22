# via-issuer-test

## The test for the via-issuer project

This is the test for the via-issuer project, using Truffle and ganache-cli.

### Steps

1.  To compile the project, change to the root of the directory where the project is located:\
``` cd <the root of the directory where the project is located> ```

2.  ``` truffle compile ```

3.  For local testing make sure to have a test blockchain such as Ganache or [Ganache Cli] installed and running before executing migrate.
Here we use the [Ganache Cli] for the test. So we should open the new terminal window and run the ganache-cli first:\
``` ganache-cli --allowUnlimitedContractSize ```

4.  ``` truffle migrate ```



[Ganache Cli]: https://github.com/trufflesuite/ganache-cli

