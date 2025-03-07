# Summary

[Introduction](./README.md)

# Getting Started

- [Installation](./getting-started/installation.md)
- [First Steps with Foundry](./getting-started/first-steps.md)

# Projects

- [Creating a New Project](./projects/creating-a-new-project.md)
- [Working on an Existing Project](./projects/working-on-an-existing-project.md)
- [Dependencies](./projects/dependencies.md)
- [Project Layout](./projects/project-layout.md)

# Forge Overview

- [Overview of Forge](forge/README.md)
- [Tests](./forge/tests.md)
  - [Writing Tests](./forge/writing-tests.md)
  - [Cheatcodes](./forge/cheatcodes.md)
  - [Forge Standard Library Overview](./forge/forge-std.md)
  - [Understanding Traces](./forge/traces.md)
  - [Forking Mode](./forge/forking-mode.md)
<!--  - [Coverage Reports]() !-->
- [Advanced Testing](./forge/advanced-testing.md)
  - [Fuzz Testing](./forge/fuzz-testing.md)
<!--  - [Invariant Testing]() !-->
<!--  - [Symbolic Testing]() !-->
<!--  - [Table Testing]() !-->
<!--  - [Mutation Testing]() !-->
<!-- - [Linting and Formatting]() !-->
<!-- - [Generating Documentation]() !-->
- [Deploying and Verifying](./forge/deploying.md)
- [Gas Tracking](./forge/gas-tracking.md)
  - [Gas Reports](./forge/gas-reports.md)
  - [Gas Snapshots](./forge/gas-snapshots.md)
- [Debugger](./forge/debugger.md)

# Cast Overview

- [Overview of Cast](./cast/README.md)

# Configuration

- [Configuring with `foundry.toml`](./config/README.md)
- [Continuous Integration](./config/continous-integration.md)
- [Integrating with VSCode](./config/vscode.md)
- [Shell Autocompletion](./config/shell-autocompletion.md)
- [Static Analyzers](./config/static-analyzers.md)

# Tutorials

- [Creating an NFT with Solmate](./tutorials/solmate-nft.md)
- [Docker and Foundry](./tutorials/foundry-docker.md)
<!-- - [Incremental Adoption]() !-->

# Appendix

- [FAQ](./faq.md)
- [References](./reference/README.md)
  - [`forge` Commands](./reference/forge/README.md)
    - [General Commands](./reference/forge/general-commands.md)
      - [forge](./reference/forge/forge.md)
      - [forge help](./reference/forge/forge-help.md)
      - [forge completions](./reference/forge/forge-completions.md)
    - [Project Commands](./reference/forge/project-commands.md)
      - [forge init](./reference/forge/forge-init.md)
      - [forge install](./reference/forge/forge-install.md)
      - [forge update](./reference/forge/forge-update.md)
      - [forge remove](./reference/forge/forge-remove.md)
      - [forge config](./reference/forge/forge-config.md)
      - [forge remappings](./reference/forge/forge-remappings.md)
      - [forge tree](./reference/forge/forge-tree.md)
    - [Build Commands](./reference/forge/build-commands.md)
      - [forge build](./reference/forge/forge-build.md)
      - [forge clean](./reference/forge/forge-clean.md)
      - [forge inspect](./reference/forge/forge-inspect.md)
    - [Test Commands](./reference/forge/test-commands.md)
      - [forge test](./reference/forge/forge-test.md)
      - [forge snapshot](./reference/forge/forge-snapshot.md)
    - [Deploy Commands](./reference/forge/deploy-commands.md)
      - [forge create](./reference/forge/forge-create.md)
      - [forge verify-contract](./reference/forge/forge-verify-contract.md)
      - [forge verify-check](./reference/forge/forge-verify-check.md)
      - [forge flatten](./reference/forge/forge-flatten.md)
    - [Utility Commands](./reference/forge/utility-commands.md)
      - [forge run](./reference/forge/forge-run.md)
      - [forge bind](./reference/forge/forge-bind.md)
  - [`cast` Commands](./reference/cast/README.md)
    - [General Commands](./reference/cast/general-commands.md)
      - [cast](./reference/cast/cast.md)
      - [cast help](./reference/cast/cast-help.md)
      - [cast completions](./reference/cast/cast-completions.md)
    - [Chain Commands](./reference/cast/chain-commands.md)
      - [cast chain-id](./reference/cast/cast-chain-id.md)
      - [cast chain](./reference/cast/cast-chain.md)
      - [cast client](./reference/cast/cast-client.md)
    - [Transaction Commands](./reference/cast/transaction-commands.md)
      - [cast publish](./reference/cast/cast-publish.md)
      - [cast receipt](./reference/cast/cast-receipt.md)
      - [cast send](./reference/cast/cast-send.md)
      - [cast call](./reference/cast/cast-call.md)
      - [cast tx](./reference/cast/cast-tx.md)
      - [cast run](./reference/cast/cast-run.md)
      - [cast estimate](./reference/cast/cast-estimate.md)
      - [cast access-list](./reference/cast/cast-access-list.md)
    - [Block Commands](./reference/cast/block-commands.md)
      - [cast find-block](./reference/cast/cast-find-block.md)
      - [cast gas-price](./reference/cast/cast-gas-price.md)
      - [cast block-number](./reference/cast/cast-block-number.md)
      - [cast basefee](./reference/cast/cast-basefee.md)
      - [cast block](./reference/cast/cast-block.md)
      - [cast age](./reference/cast/cast-age.md)
    - [Account Commands](./reference/cast/account-commands.md)
      - [cast balance](./reference/cast/cast-balance.md)
      - [cast storage](./reference/cast/cast-storage.md)
      - [cast proof](./reference/cast/cast-proof.md)
      - [cast nonce](./reference/cast/cast-nonce.md)
      - [cast code](./reference/cast/cast-code.md)
    - [ENS Commands](./reference/cast/ens-commands.md)
      - [cast lookup-address](./reference/cast/cast-lookup-address.md)
      - [cast resolve-name](./reference/cast/cast-resolve-name.md)
      - [cast namehash](./reference/cast/cast-namehash.md)
    - [Etherscan Commands](./reference/cast/etherscan-commands.md)
      - [cast etherscan-source](./reference/cast/cast-etherscan-source.md)
    - [ABI Commands](./reference/cast/abi-commands.md)
      - [cast abi-encode](./reference/cast/cast-abi-encode.md)
      - [cast 4byte](./reference/cast/cast-4byte.md)
      - [cast 4byte-decode](./reference/cast/cast-4byte-decode.md)
      - [cast 4byte-event](./reference/cast/cast-4byte-event.md)
      - [cast calldata](./reference/cast/cast-calldata.md)
      - [cast pretty-calldata](./reference/cast/cast-pretty-calldata.md)
      - [cast --abi-decode](./reference/cast/cast--abi-decode.md)
      - [cast --calldata-decode](./reference/cast/cast--calldata-decode.md)
    - [Conversion Commands](./reference/cast/conversion-commands.md)
      - [cast --from-bin](./reference/cast/cast--from-bin.md)
      - [cast --from-fix](./reference/cast/cast--from-fix.md)
      - [cast --from-utf8](./reference/cast/cast--from-utf8.md)
      - [cast --to-ascii](./reference/cast/cast--to-ascii.md)
      - [cast --to-bytes32](./reference/cast/cast--to-bytes32.md)
      - [cast --to-dec](./reference/cast/cast--to-dec.md)
      - [cast --to-fix](./reference/cast/cast--to-fix.md)
      - [cast --to-hex](./reference/cast/cast--to-hex.md)
      - [cast --to-hexdata](./reference/cast/cast--to-hexdata.md)
      - [cast --to-int256](./reference/cast/cast--to-int256.md)
      - [cast --to-uint256](./reference/cast/cast--to-uint256.md)
      - [cast --to-unit](./reference/cast/cast--to-unit.md)
      - [cast --to-wei](./reference/cast/cast--to-wei.md)
    - [Utility Commands](./reference/cast/utility-commands.md)
      - [cast sig](./reference/cast/cast-sig.md)
      - [cast keccak](./reference/cast/cast-keccak.md)
      - [cast compute-address](./reference/cast/cast-compute-address.md)
      - [cast interface](./reference/cast/cast-interface.md)
      - [cast index](./reference/cast/cast-index.md)
      - [cast --concat-hex](./reference/cast/cast--concat-hex.md)
      - [cast --max-int](./reference/cast/cast--max-int.md)
      - [cast --min-int](./reference/cast/cast--min-int.md)
      - [cast --max-uint](./reference/cast/cast--max-uint.md)
      - [cast --to-checksum-address](./reference/cast/cast--to-checksum-address.md)
    - [Wallet Commands](./reference/cast/wallet-commands.md)
      - [cast wallet](./reference/cast/cast-wallet.md)
      - [cast wallet new](./reference/cast/cast-wallet-new.md)
      - [cast wallet address](./reference/cast/cast-wallet-address.md)
      - [cast wallet sign](./reference/cast/cast-wallet-sign.md)
      - [cast wallet vanity](./reference/cast/cast-wallet-vanity.md)
      - [cast wallet verify](./reference/cast/cast-wallet-verify.md)
  - [Config Reference](./reference/config.md)
  - [Forge Standard Library Reference](./reference/forge-std/README.md)
    - [Std Cheats](./reference/forge-std/std-cheats.md)
      - [`skip`](./reference/forge-std/skip.md)
      - [`rewind`](./reference/forge-std/rewind.md)
      - [`hoax`](./reference/forge-std/hoax.md)
      - [`startHoax`](./reference/forge-std/startHoax.md)
      - [`deal`](./reference/forge-std/deal.md)
      - [`deployCode`](./reference/forge-std/deployCode.md)
    - [Std Errors](./reference/forge-std/std-errors.md)
      - [`assertionError`](./reference/forge-std/assertionError.md)
      - [`arithmeticError`](./reference/forge-std/arithmeticError.md)
      - [`divisionError`](./reference/forge-std/divisionError.md)
      - [`enumConversionError`](./reference/forge-std/enumConversionError.md)
      - [`encodeStorageError`](./reference/forge-std/encodeStorageError.md)
      - [`popError`](./reference/forge-std/popError.md)
      - [`indexOOBError`](./reference/forge-std/indexOOBError.md)
      - [`memOverflowError`](./reference/forge-std/memOverflowError.md)
      - [`zeroVarError`](./reference/forge-std/zeroVarError.md)
    - [Std Storage](./reference/forge-std/std-storage.md)
  - [DSTest Reference](./reference/ds-test.md)
  - [Cheatcodes Reference](./cheatcodes/README.md)
    - [Environment](./cheatcodes/environment.md)
      - [`warp`](./cheatcodes/warp.md)
      - [`roll`](./cheatcodes/roll.md)
      - [`fee`](./cheatcodes/fee.md)
      - [`chainId`](./cheatcodes/chain-id.md)
      - [`store`](./cheatcodes/store.md)
      - [`load`](./cheatcodes/load.md)
      - [`etch`](./cheatcodes/etch.md)
      - [`deal`](./cheatcodes/deal.md)
      - [`prank`](./cheatcodes/prank.md)
      - [`startPrank`](./cheatcodes/start-prank.md)
      - [`stopPrank`](./cheatcodes/stop-prank.md)
      - [`record`](./cheatcodes/record.md)
      - [`accesses`](./cheatcodes/accesses.md)
      - [`setNonce`](./cheatcodes/set-nonce.md)
      - [`getNonce`](./cheatcodes/get-nonce.md)
      - [`mockCall`](./cheatcodes/mock-call.md)
      - [`clearMockedCalls`](./cheatcodes/clear-mocked-calls.md)
    - [Assertions](./cheatcodes/assertions.md)
      - [`expectRevert`](./cheatcodes/expect-revert.md)
      - [`expectEmit`](./cheatcodes/expect-emit.md)
      - [`expectCall`](./cheatcodes/expect-call.md)
    - [Fuzzer](./cheatcodes/fuzzer.md)
      - [`assume`](./cheatcodes/assume.md)
    - [External](./cheatcodes/external.md)
      - [`ffi`](./cheatcodes/ffi.md)
      - [`getCode`](./cheatcodes/get-code.md)
    - [Utilities](./cheatcodes/utilities.md)
      - [`addr`](./cheatcodes/addr.md)
      - [`sign`](./cheatcodes/sign.md)
      - [`label`](./cheatcodes/label.md)
