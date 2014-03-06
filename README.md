llvm_compiler_research
======================

For archival/read-only purposes only.

This was some research I embarked on a few years back around LLVM and its' affects on performance vs GCC by benchmarking "real world" applications.

LLVM interested me because of its' modular design and link time optimizations (LTO); which I thought could make a huge impact on loading oft-bloated sections like .data or .bss due to lazy engineering. Note, I am also guilty of "less than efficient" engineering but that's why LTO intrigued me!

This was before LLVM became Apple's primary compiler, since when it has become more mainstream.
