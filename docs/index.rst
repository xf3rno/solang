Solang Solidity Compiler
========================

.. image:: web3_foundation_grants_badge_black.svg
    :width: 640px
    :alt: Funded by the web3 foundation
    :align: center
    :target: https://github.com/w3f/Web3-collaboration/blob/master/grants/accepted_grant_applications.md#wave-4

Welcome to the Solang Solidity Compiler, the portable Solidity compiler.
Using Solang, you can compile smart contracts written in
`Solidity <https://en.wikipedia.org/wiki/Solidity>`_
for `Parity Substrate <https://substrate.dev/>`_,
`Solana <https://www.solana.com/>`_,
`Sawtooth Sabre <https://github.com/hyperledger/sawtooth-sabre>`_, and
`Ethereum ewasm <https://github.com/ewasm/design>`_. It uses the
`llvm <https://www.llvm.org/>`_ compiler framework to produce WebAssembly
(wasm) or BPF contract code. As result, the output is highly optimized, which saves you in gas costs.

Solang aims for source file compatibility with the Ethereum EVM Solidity compiler,
version 0.7. Where differences exists, this is noted in the :ref:`language documentation <language>`.
Also, check our :ref:`status` page.
The repository can be found on `github <https://github.com/hyperledger-labs/solang>`_
and we have a `channel on chat.hyperledger.org <https://chat.hyperledger.org/channel/solang>`_.

.. toctree::
   :maxdepth: 3
   :caption: Contents:

   installing
   status
   running
   language
   optimizer
   extension
   examples
   contributing
