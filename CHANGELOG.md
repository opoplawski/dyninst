# Change Log

## [10.0.0](https://github.com/dyninst/dyninst/tree/10.0.0) (2018-11-07)
[Full Changelog](https://github.com/dyninst/dyninst/compare/v9.3.2...10.0.0)

**Implemented enhancements:**

- Migrate Dyninst from libdwarf to libdw [\#328](https://github.com/dyninst/dyninst/issues/328)
- Auto-detect Cilk [\#326](https://github.com/dyninst/dyninst/issues/326)
- Make ParseAPI \(optionally\) multi-threaded [\#145](https://github.com/dyninst/dyninst/issues/145)

**Fixed bugs:**

- Misc. x86 Decoding Issues [\#372](https://github.com/dyninst/dyninst/issues/372)
- Segfault when singleton\_object\_pool reallocs [\#359](https://github.com/dyninst/dyninst/issues/359)
- assert fails at insnCodeGen::generateBranchViaTrap [\#356](https://github.com/dyninst/dyninst/issues/356)
- Incorrect function boundaries for functions sharing code [\#149](https://github.com/dyninst/dyninst/issues/149)

**Closed issues:**

- Intel TBB install [\#500](https://github.com/dyninst/dyninst/issues/500)
- Compilation Error [\#491](https://github.com/dyninst/dyninst/issues/491)
- Build fails on Arch Linux [\#486](https://github.com/dyninst/dyninst/issues/486)
- Power 8 Instrimentation stack frame generation destroys vector register values [\#484](https://github.com/dyninst/dyninst/issues/484)
- Missing Vector Instructions and Reused Opcodes in Power 8 [\#483](https://github.com/dyninst/dyninst/issues/483)
- Codegen gen.point\(\) fails in most cases on Power \(returns NULL\) [\#482](https://github.com/dyninst/dyninst/issues/482)
- Power support for code generation of long branch calls  \(i.e.  branch with link to SPR\) [\#481](https://github.com/dyninst/dyninst/issues/481)
- relocation of branch +0x4 causes erratic behaviors on PowerPC [\#480](https://github.com/dyninst/dyninst/issues/480)
- Handling Relocation of Power 8 Function Preamble  [\#479](https://github.com/dyninst/dyninst/issues/479)
- SymtabAPI dumps core when reading an exception table for a KNL \(provided\) binary [\#477](https://github.com/dyninst/dyninst/issues/477)
- PCWidget::PCtoReturnAddr sets LR unnecessarily on non-x86 architectures [\#474](https://github.com/dyninst/dyninst/issues/474)
- Spack Build Fails with missing dependency on libiberty [\#473](https://github.com/dyninst/dyninst/issues/473)
- how to print the instruction which contains “cmp” [\#465](https://github.com/dyninst/dyninst/issues/465)
- Instrumentation blocks not saving/restoring correct registers. [\#461](https://github.com/dyninst/dyninst/issues/461)
- Segfault [\#456](https://github.com/dyninst/dyninst/issues/456)
- InsertSnippet does not check if "when" parameter is legal [\#455](https://github.com/dyninst/dyninst/issues/455)
- Heuristics to determined prologues [\#454](https://github.com/dyninst/dyninst/issues/454)
- processCreate crashed on aarch64 [\#449](https://github.com/dyninst/dyninst/issues/449)
- virtual bool AstCallNode::initRegisters\(codeGen&\): Assertion `callee' failed. Aborted \(core dumped\) [\#442](https://github.com/dyninst/dyninst/issues/442)
- undefined reference to symbol '\_ZNK7Dyninst14InstructionAPI11Instruction4sizeEv [\#440](https://github.com/dyninst/dyninst/issues/440)
- cannot find -ldwarf?  [\#439](https://github.com/dyninst/dyninst/issues/439)
- xdrrec\_create\(\) type cast error: char\* vs. void\* [\#438](https://github.com/dyninst/dyninst/issues/438)
- Error in build boost c++ library during installing Dyninst in Linux Ubuntu [\#435](https://github.com/dyninst/dyninst/issues/435)
- dyninst not saving/restoring a register used in insertSnippet [\#434](https://github.com/dyninst/dyninst/issues/434)
- Non-returning function analysis involving tail calls [\#433](https://github.com/dyninst/dyninst/issues/433)
- Several problems for analyzing powerpc binarieson x86 [\#432](https://github.com/dyninst/dyninst/issues/432)
- Patch without libdyninstAPI\_RT.so [\#428](https://github.com/dyninst/dyninst/issues/428)
- testsuite failures with separate debuginfo [\#423](https://github.com/dyninst/dyninst/issues/423)
- make\[2\]: \*\*\* No rule to make target `libiberty/libiberty.a', needed by `common/libcommon.so.9.3.2'.  Stop. [\#420](https://github.com/dyninst/dyninst/issues/420)
- make failing in latest branch [\#419](https://github.com/dyninst/dyninst/issues/419)
- Serious problem introduced when libdw was adopted [\#415](https://github.com/dyninst/dyninst/issues/415)
- emitElf::createLoadableSections uses hard-coded sh\_info [\#405](https://github.com/dyninst/dyninst/issues/405)
- Memory corruption in ROSE memory pool allocator [\#400](https://github.com/dyninst/dyninst/issues/400)
- ebx should be callee-saved [\#399](https://github.com/dyninst/dyninst/issues/399)
- getFirstSymbol\(\)-\>getMangledName SIGSEGV in PLT stub processing [\#396](https://github.com/dyninst/dyninst/issues/396)
- disassembling issue [\#395](https://github.com/dyninst/dyninst/issues/395)
- parseAPI shouldn't segfault if c++filt cannot demangle a symbol [\#390](https://github.com/dyninst/dyninst/issues/390)
- The value of BPatch\_registerExpr\(BPatch\_register reg\) [\#388](https://github.com/dyninst/dyninst/issues/388)
- Dyninst doesn't instrument the binary when it is compiled with -O3 flag \(g++\) [\#384](https://github.com/dyninst/dyninst/issues/384)
- The address of instructions [\#380](https://github.com/dyninst/dyninst/issues/380)
- Thunk call judgement condition [\#379](https://github.com/dyninst/dyninst/issues/379)
- Is there any APIs that can be used for finding the indirect calls? [\#378](https://github.com/dyninst/dyninst/issues/378)
- force boost build and force boost install [\#374](https://github.com/dyninst/dyninst/issues/374)
- Compilation issue wrt to libdwarf an then zlib [\#373](https://github.com/dyninst/dyninst/issues/373)
- CFG of stripped binary is empty [\#371](https://github.com/dyninst/dyninst/issues/371)
- BPatch\_statement::fileName\(\) returns the empty string since somewhere between 9.2.0...9.3.0 [\#363](https://github.com/dyninst/dyninst/issues/363)
- Power ABI v2 abstractions [\#119](https://github.com/dyninst/dyninst/issues/119)

**Merged pull requests:**

- Vector instruction support on Power and recycled opcode [\#498](https://github.com/dyninst/dyninst/pull/498) ([mxz297](https://github.com/mxz297))
- Build fixes for parallel building and xdr-related issues [\#496](https://github.com/dyninst/dyninst/pull/496) ([LER0ever](https://github.com/LER0ever))
- Merge parallel code parsing [\#488](https://github.com/dyninst/dyninst/pull/488) ([mxz297](https://github.com/mxz297))
- Power8 instrumentation fix [\#485](https://github.com/dyninst/dyninst/pull/485) ([mxz297](https://github.com/mxz297))
- symtab: fix memory error in Statement::getFile [\#469](https://github.com/dyninst/dyninst/pull/469) ([rafzi](https://github.com/rafzi))
- Vector categories merge into master [\#463](https://github.com/dyninst/dyninst/pull/463) ([jgalarowicz](https://github.com/jgalarowicz))
- Fix for crashing on relocating at unistrumentable points [\#460](https://github.com/dyninst/dyninst/pull/460) ([bwelton](https://github.com/bwelton))
- New walker to walk out of Instrimentation Frames FP [\#452](https://github.com/dyninst/dyninst/pull/452) ([bwelton](https://github.com/bwelton))
- Fixes for testsuite failures on powerv7 and block boundary aligning for overlapping instructions [\#446](https://github.com/dyninst/dyninst/pull/446) ([mxz297](https://github.com/mxz297))
- Remove unused rpc/xdr references. [\#445](https://github.com/dyninst/dyninst/pull/445) ([stanfordcox](https://github.com/stanfordcox))
- Very minor clean-up a particualrly ugly piece of code. [\#441](https://github.com/dyninst/dyninst/pull/441) ([thomasdullien](https://github.com/thomasdullien))
- Fixes for non-returning functions, endianness for cross architecture parsing, and powerpc instruction decoding [\#437](https://github.com/dyninst/dyninst/pull/437) ([mxz297](https://github.com/mxz297))
- add missing initialization for flags when Elf\_X is a memory image [\#430](https://github.com/dyninst/dyninst/pull/430) ([jmellorcrummey](https://github.com/jmellorcrummey))
- Fix sh\_info for VERNEED section [\#427](https://github.com/dyninst/dyninst/pull/427) ([nedwill](https://github.com/nedwill))
- Bugfixes windows [\#418](https://github.com/dyninst/dyninst/pull/418) ([mitalirawat](https://github.com/mitalirawat))
- AArch32 ARM Parsing Support [\#417](https://github.com/dyninst/dyninst/pull/417) ([rchyena](https://github.com/rchyena))
- Parallel Parsing changes [\#416](https://github.com/dyninst/dyninst/pull/416) ([jmellorcrummey](https://github.com/jmellorcrummey))
- Add linux-vdso64.so.1 to the library blacklist. [\#414](https://github.com/dyninst/dyninst/pull/414) ([stanfordcox](https://github.com/stanfordcox))
- Handle R\_X86\_64\_IRELATIVE relocation. [\#413](https://github.com/dyninst/dyninst/pull/413) ([stanfordcox](https://github.com/stanfordcox))
- Add basic support for EM\_CUDA binary type [\#410](https://github.com/dyninst/dyninst/pull/410) ([jmellorcrummey](https://github.com/jmellorcrummey))
- Fix the crash issue of retee [\#408](https://github.com/dyninst/dyninst/pull/408) ([mxz297](https://github.com/mxz297))
- fix dwarf symbol frame [\#403](https://github.com/dyninst/dyninst/pull/403) ([sashanicolas](https://github.com/sashanicolas))
- Merging my jump table improvements, att\_syntax, and arm semantics [\#401](https://github.com/dyninst/dyninst/pull/401) ([mxz297](https://github.com/mxz297))
- Fixing the destruction of objects under process control api. [\#382](https://github.com/dyninst/dyninst/pull/382) ([sashanicolas](https://github.com/sashanicolas))
- Add FORCE\_BOOST CMake option for @lee218llnl [\#381](https://github.com/dyninst/dyninst/pull/381) ([wrwilliams](https://github.com/wrwilliams))
- fix a bug when generating relocation index [\#370](https://github.com/dyninst/dyninst/pull/370) ([fengharry](https://github.com/fengharry))
- Clean up and refactor reaching definitions for better readability [\#369](https://github.com/dyninst/dyninst/pull/369) ([morehouse](https://github.com/morehouse))
- Sfm/fixes/indirection fixes [\#368](https://github.com/dyninst/dyninst/pull/368) ([morehouse](https://github.com/morehouse))
- Pull request for arm64/feature/relocation into master [\#367](https://github.com/dyninst/dyninst/pull/367) ([ssunny7](https://github.com/ssunny7))
- Pull request for att\_syntax into master [\#366](https://github.com/dyninst/dyninst/pull/366) ([ssunny7](https://github.com/ssunny7))
- Prevent non-PIC thunks from being classified as such [\#365](https://github.com/dyninst/dyninst/pull/365) ([morehouse](https://github.com/morehouse))
- Sfm/feature/reaching defs [\#364](https://github.com/dyninst/dyninst/pull/364) ([morehouse](https://github.com/morehouse))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*