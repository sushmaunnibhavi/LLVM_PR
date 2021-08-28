# LLVM CONTRIBUTIONS:

Contributed to https://github.com/llvm/llvm-project .
Worked on adding support for Motorola 68k backend into the Global Instruction Selection
framework, to be able to translate LLVM IR into machine specific IR suitable for the m68k architecture. Implemented
call lowerings for multiple operations in four major stages: IRTranslator stage, Legalizer stage, RegBankSelect stage and
the InstructionSelect stage. The changes and patches have been successfully upstreamed into the LLVM codebase.

## Code contributions:
- https://reviews.llvm.org/D101819
  Reviewed by: Anshil Gandhi, Min-Yih Hsu, Amara Emerson, Simon Pilgrim
  - Merged into main: https://reviews.llvm.org/rG2193347e72fad6a78ce4a96c8d89f9a43a028e79
- https://reviews.llvm.org/D104542
  Reviewed by: Anshil Gandhi, Min-Yih Hsu
  - Merged into main: https://reviews.llvm.org/rG8f43407a07f015ca9a7543c6a0b5bde3918f9a0e
- https://reviews.llvm.org/D105332
  Reviewed by: Anshil Gandhi, Min-Yih Hsu
  - Merged into main: https://reviews.llvm.org/rG086370faee2a85c40855893537740c14217131e3
- https://reviews.llvm.org/D105536
  Reviewed by: Anshil Gandhi, Min-Yih Hsu
  - Merged into main: https://reviews.llvm.org/rGaaccc985a88db4fb7ae4be341db62bb1fe974102
- https://reviews.llvm.org/D107542
  Reviewed by: Anshil Gandhi, Min-Yih Hsu
  - Merged into main: https://reviews.llvm.org/rG7bdce6bcbda3a8b7dcdac6a7d8fb1083912830d7

## Documentation contributions:
- https://reviews.llvm.org/D100053
  Reviewed by: Jonas Devlieghere
- https://reviews.llvm.org/D100125
  Reviewed by: Shivam Gupta
- https://reviews.llvm.org/D100254
  Reviewed by: Daniel Sanders
- https://reviews.llvm.org/D101227
  Reviewed by: Shivam Gupta, Dominik Montada
- https://reviews.llvm.org/D101433
  Reviewed by: Shivam Gupta, Adrian McCarthy
