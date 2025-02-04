# portfolio

## project one:
- (completed) [project one config notes](./project-one-config-notes.md)
- (completed) [project one advanced llvm notes](./project-one-advanced-llvm-notes.md)
- (in progress) [project one summary notes](./project-one-summary-notes.md)
- (in progress) [project one frontend notes](./project-one-frontend-notes.md)

## project two:
- (in progress) [project two plan notes](./project-two-plan-notes.md)

## project three:
- (in progress) [project three plan notes](./project-three-plan-notes.md)


## overall strategy:

- meta-level
- high-level
- mid-level
- and corresponding low-level code
- use parallel visual and verbal problem solving for present this portfolio

# meta-level:

## meta-level frontend ui/ux and content

#### ui/ux

- TL;DRs & minimalistic text content always
- original lucidchart diagrams (w simple titles) for:
  - (*** mandatory) explanation of this github repo directory layout/structures and key code functionality
  - LLVM/MLIR/Modular IRs & infrastructure/tooling & build/compile orders
  - this portfolio's color palette and design elements?
  - generic hardware-to-software stack
  - math and physics topics i've studied
  - how ontologic classification of reality, cognitive science, & linguistics correspond to OOP (& maybe show context of branches of philosophy)
  - elements of prog langs i know (C++, Java, JavaScript, Python, Rust, Ruby, HTML, CSS)
  - history of significant LLM & ML paradigms' research papers, APIs, etc.
  - history of ISA breakthroughs and technology, i.e. SIMD to SIMT
  - chart of metatheory, metalinguistics, metaontology, metaphilosophy, mental models, metaprogrammaing, metaML, metalogic etc.
- Excel charts, Gantt charts, Sankey diagram, classification custom double axis charts, etc. for tracking this portfolio's progress/timeline/roadmap
- aesthetic considerations with which to create Figma UI dark mode designs for this portfolio site (including Jupyter notebook & terminal aesthetics) (also including resume, twitter, github, and linkedin)
  - truly modern flat Google open-source material design paradigm (industry-standard accessible contrasts, font sizes, etc.)
  - metamodernism (current haute/rare aesthetic paradigm)
  - please reference the specific examples on https://cari.institute/aesthetics
    - cassette futurism (for terminal & buttons)
    - corporate hippie (reminds me of corporate flat in general)
    - cyberbougie (color palette)
    - eco-beige (consider this palette insteaq of cyberbougie palette because is last/current-gen pop culture aesthetic PLUS*** it invokes DAYTIME)
    - factory pomo (for lang icons/logos section)
    - genericana (reminds me of certain corporate elements)
    - gen x soft club (because of minimalism and palette)
    - laser grid (because it reminds me of current AI-generated art paradigm themes)
    - nu-brutalism (flat design, ability to include many cards at once, and vintage yet post-modern fonts)
    - pixelscape (fun aesthetic for programming & reminds me of the semiconductor chip design metaphor/visualizations)
    - pastel southwestern (for even softer palette than cyberbougie but similar)
    - pastel fantasy (also reminds me of current AI art paradigm)
    - superflat pop (because it was very ahead of its time in terms of flat, palette, themes, and art paradigm)
    - synthwave (essentially dark cyberbougie palette but more neon; also like laser grid)
    - vaporwave (like synthwave properties plus yellow in palette and additionally evokes Y2K and frutiger aero)
    - vector minimalism (evokes last-gen corporate design)
    - Y2K aesthetic (because good to know when cyberbougie-esque palette started and how it evolved; also interesting themes)
    - zen-x (reminds me of eco-beige yet much more calm and feels like how i feel when i can get in deep flow with code/work)

#### personal bio plan:

- icons for all langs i know
- quick bio
- photo
- links:
  - programming-based twitter
  - linkedin
  - my github home page
 



## meta-level backend

- TL;DRs & minimalistic text content always
- at least one portfolio page with a Jupyter notebook:
  - use the classic MNIST dataset?
  - demo one of current promising ML theories?
  - demo integration of many current promising ML theories
  - ability to change Jupyter code to see diff output (***to prove functionality)
- buttons at bottom of a Jupyter notework to:
  - compile with LLVM
  - compile with MLIR
  - compile with Mojo/Modular
- outputs of IR & description
- outputs of ISA & description
- stored in GCP/Azure?
- links to check results:
  - block of text/code to copy into GPT 3.5 and Gemini, etc.
  - links to LLVM/MLIR/Modular GH repos but with my process (bash commands, configs, etc.)






# high-level plans (frontend and backend)


## high-level frontend tech stack & ui/ux

#### tech stack

- components/styling:
  - see if i can use old portfolio's HTML & CSS via Bootstrap & Sass
  - otherwise, use Google's Material Design components will be enough for relatively static site
  - if i need dynamic components, then React if I can re-configure the build toolchain
- build toolchain: yarn, parcel & GitHub Pages
  - if parcel is broken, use webpack built into the standard react-create-app as long as it's compatible with GitHub Pages

note:
- ^these choices don't have to be ideal because i'm not looking for frontend jobs anymore. they just have to work.
- the page should be mostly static with minimal dynamic elements (no embedded jupyter notebook like i had researched)

#### ui/ux

- easily be able to copy code sections from my site and link to a free online Jupyter notebook to test code
- one page for each project I'm demoing (basically a graphics-based minimal-text code walkthrough but also for non-technical people)
  - one LLVM project (c++)
  - one Modular/MLIR project 
  - one CUDA project
- great non-techincal report for portfolio website page with:
   - excel graphs/charts w lucidchart aesthetic, etc.
   - architecture map
   - copyable code
   - link to Jupyter-notebook-type sites for proof


## high-level backend plan:

#### project progression ideas: (today is Mar 14, 2024)
  
1. llvm project (SIMT?)
   - c++
   - extremely basic but good representation of the c++ standard library
     - study quick map of c++ std for:
       - I/O file read/write
       - class/object
       - list
       - data types to demo the stack & heap
       - recursive loop if possible
       - basic search algo DFS/BFS recursion and find the exit condition
     - should correspond to basic LLVM IR
     - still study std LLVM IR though.
   - **_apr 4 update_**: finished it with one basic block
3. modular project (SIMT?)
   - update: 
   - mojo(python)/MLIR IR
   - MNIST dataset unless i can think of something better
     - can i apply current models to this?
     - which is the best current singular model to use for this?
   - try to make the project run in the Modular browser env for proving the project
4. cuda project
   - nvcc/ptx (parallel thread execution) (SIMT?)
   - **_apr 4 update_**: demo c++ std lib & mult basic blocks here instead of project one.
   - choose: c/c++ or python/PyCUDA
     - do i want to demonstrate just my IR experience or possibly also ML experience?
   - can i do an integration of all best models thus far?
   - search kaggle for an already-cleaned dataset and then do
     - basic fundamental principles
     - feature engineering
     - regression
     - modeling
   
#### notes:
- diff repo for each one
- where does SIMT apply?

- plan complexity levels and skills demoed for each
- plan order in which i do them
- plan how much time dedicated to each and deadlines
- 3 projects total because combine Modular/MLIR

#### time left:

2.5 months till first round of applications:
- last 2 weeks mar
- april
- may

then 1.5 more months till second round of applications:
- june
- first 2 weeks july 

#### project timelines

- LLVM project 
  - ideal:
    - total time: 4 weeks
    - finished by: April 30
    - (_**code done apr 4**_)
  - deadline: May 31

- Modular project 
  - ideal:
    - total time: 6 weeks
    - finished by: May 31
  - deadline: May 31 or July 15 if i'm really struggling

- CUDA project
  - ideal:
    - total time: 6 weeks
    - finished by: July 15
  - deadline: July 15 (to begin final applications Aug 1)
 





# mid-level plans

## mid-level frontend plan

consider all these at same time:
- build toolchain
- v0.dev can create the UI & UX components i want
- nice UI design (diff design for each project?)


## mid-level backend plan 

todo list:
1. simplify high-level backend plan for project one (made progress Fri Mar 15)
2. start going on low-level backend plan
3. work on backend M-F
4. take a look at frontend on the weekends

1. llvm project
   - c++ [c++ standard library](https://en.cppreference.com/w/cpp/header)
   - extremely basic but good representation of the c++ standard library
     - study quick map of c++ std for:
       - I/O file read/write
       - class/object
       - list
       - data types to demo the stack & heap
       - recursive loop if possible
       - basic search algo DFS/BFS recursion and find the exit condition
     - should correspond to basic LLVM IR
       - C++ LLVM metaphor concepts:
         - abstraction/standardization - abstract away low-level details for portable code; high-level abstraction of SEMANTICS
         - generics/templates which are data structures and algos for many data ttypes
         - modularity/composition (of containers, algos, I/O) to create complexity (IR: basic blocks, instructions, functions)
         - optimizations/transformation  
     - still study std LLVM IR though. :::
       - basic blocks (single entry point & single exit point (except for branches, loops, etc.))
       - instructions (arith ops, memory accesses, function calls and control flow inst) mnemonic codes - SSA form (Static Single Assignment)
       - functions (name and signature (return type and params) and body) (`define`)
       - values: constants, vars, and results ::: are types
       - data types: int, float, vect, pointers, structures, arrays and user-defined types
       - global vars accessed from any function (starts with `@`)

      
notes:
  - CUDA can use LLVM to create a SIMT-execution-model-style ISA ("instructions for managing threads, accessing memory, performing arithmetic and logical operations, and controlling execution flow.")
  - how do basic blocks handle control flow instructions? (branches between basic blocks have explicit instructions)
  - SSA: "SSA is a form of intermediate representation used in compiler design, particularly in optimizing compilers. In SSA form, each variable is assigned exactly once, and each use of the variable refers to that specific definition. This property simplifies data-flow analysis and enables certain optimizations such as common subexpression elimination and dead code elimination."
  - ISA "encompasses the set of instructions that a processor architecture supports, along with their encoding, semantics, and behavior"


# low-level plans

## low-level frontend plan 

- try out v0.dev next
- actually try out vercel frontend components tools

## low-level backend plan 

1. llvm project 
  - c++ content: primitive var cast to object var in a list in an object sounds ideal (no read/write needed cause I'm not a networking specialist)
  - c++ algo options:
    - (no) RNN recursive neural networks - recursive algo
    - (no) GBMs gradient boosting machines - tree-based algos (also decision trees, random forest, 
    - (no) GNNs and GCNs graph neural networks and graph convoluational networks - graph algos
    - transformer: (graph algo)
      - core component: self-attention mechanism
        - attention scores via dependencies & relationships
        - then compute weighted sums of the input embeddings, generating context-aware representations for each word
      - multiple layers processed in parallel (parallelism / concurrency / multithreading / SIMT, PTX, etc.)
      - essentially filter algos ?
      - long-range dependencies which RNNs couldnt
      - in NLP, token in sequence are nodes in graph, attention scores and edge weights btw all pairs
      - can then capture hierarchical structures efficiently
  - llvm ir: use 3 basic blocks to show how entry and exit would work in that case
    - DFS and BFS both can search graphs, doesnt matter which one, whatever works w the program
    - non-technical semantics: knowledge graph of relationship strength between objects then make a hierarchy
    - no generics is fine
    - can discuss modularity and composition (see above section for details)
    - optimizations: on purpose, use the type of loop that can be optimized 
    - transformation: ^then show how llvm ir transforms the loop
    - might need like 4 basic blocks actually for 6 relationships and one four-word sentence (then use code for input and output with slight modifications)
    - will include arith ops for wts, memory access of course (registers, cache, RAM ideally but maybe save that for projects 2 or 3)
    - will include values (vars and results)
    - make sure to use pointer but its fine w/o array and struct actually for this one
    - no global var is fine i think till later (#todo for project 2/3)
    - the function calls will be the node creations and the search
    - the control flow is the loop
    - make sure to map to SSA and talk about importance of explicit single assignments in terms of basic blocks and the looping
       
next:
- compile a c++ llvm cmake config asap or rapidly pivot to compiling it somehow in browser, etc.
- new repo and write out the algo in c++
- make the config
- examine the IR with the tooling
- get it on the frontend asap
- 3/28 note: i've been noticing SDK needs in project 1 notes file and also CUDA SDKs too:
  - [NVIDIA SDK glossary](https://developer.nvidia.com/sdk-glossary?ncid=em-even-320346-vt53&AY0sih1l1UctMMIQTiqyC6aG0vIU7hk9NTqbq_hdl8IdJheje-8uln1-X4z-2ibgdTCXrtCR6nme4nSZM2oaFQ&mkt_tok=MTU2LU9GTi03NDIAAAGSH2kFQN7hB2EUkz0R4yCQOaSKpCpT72cvdEC-pNi79okOwy6M5E_BiaeCznSZvrfNlYg6rNnfmrKodZKUzjQS70M5767F97VL3kGAx5nvuqSq4WGu63g)
  - additional NVIDIA resource: [Deep Learning Institute](https://www.nvidia.com/en-us/training/?ncid=em-even-886387-vt53&AY0sih1l1UctMMIQTiqyC6aG0vIU7hk9NTqbq_hdl8IdJheje-8uln1-X4z-2ibgdTCXrtCR6nme4nSZM2oaFQ&mkt_tok=MTU2LU9GTi03NDIAAAGSH2kFQCObZqwKtC-J_STITgfFWZDSCosu8VYBbsKCN8FD3qjzelrdm_VJtF9egQhWN6J-rkJvV8cXrMGaUjtCY9T7ytL86J6CS1YzTAK761Eu1Jt2coo])
  - `CMAKE_OSX_SYSROOT              /Library/Developer/CommandLineTools/SDKs/MacOSX14.4.sdk`
  -  If "LLVM" provides a separate development package or SDK, be sure it has been installed.
  -  Set the macOS system root `set(CMAKE_OSX_SYSROOT /Library/Developer/CommandLineTools/SDKs/MacOSX14.4.sdk)`

additional portfolio notes:
- remember when i had the goal to build a compiler and work that into these projects
- study leetcode arrays, for example cityscape problem; model data structures and algos concepts
- use parallel visual and verbal problem solving
- research ISO/ISEE/x86, etc. standards, protocols, etc. to see if/how they apply to these projects (esp new standards and CUDA Math API standards, etc.) (#todo for projects 2/3)

#### apr 4, 2024 next steps:
- use this doc to do project one code analysis
- archive the rest of project one high-med-low level plans out of this readme
- create frontend asap to demo project one

#### progress apr 5, 2024:
- new project one summary readme with high/mid/low levels structure

















