Today Simulation is arguably one of the most multifaceted topics that can face an Industrial Engineer in the workplace. It can also be one of the most important to a corporation, regardless of the industry. Quality, safety and productivity are all affected by Simulation, whether the issues occur in the office, on the manufacturing floor, or in a warehouse. [5] IIE Solutions Guide, Vol. 12-30, Ed. 58.A214, 1980, 1981, 1982, 1983, 1984, 1989, 1999.
Simulation is extensively being used as a tool to increase the production capacity.

Generic examples of types of computer simulations in science, which are derived from an underlying mathematical description:

 * a numerical simulation of differential equations that cannot be solved analytically, theories that involve continuous systems such as phenomena in physical cosmology, fluid dynamics (e.g. climate models, roadway noise models, roadway air dispersion models), continuum mechanics and chemical kinetics fall into this category.
 * a stochastic simulation, typically used for discrete systems where events occur probabilistically, and which cannot be described directly with differential equations (this is a discrete simulation in the above sense). Phenomena in this category include genetic drift, biochemical or gene regulatory networks with small numbers of molecules. (see also: Monte Carlo method).
[wikipedia](http://en.wikipedia.org/wiki/Computer_simulation)

Donner des exemples de systèmes qui sont modélisés et simulés.

The history of computer simulation dates back to differents times and places:

First Generation Electronic Computers (1937-1953)

 * The earliest attempt to build an electronic computer was by J. V. Atanasoff, a professor of physics and mathematics at Iowa State, in 1937. Atanasoff set out to build a machine that would help his graduate students solve systems of partial differential equations. By 1941 he and graduate student Clifford Berry had succeeded in building a machine that could solve 29 simultaneous equations with 29 unknowns. However, the machine was not programmable, and was more of an electronic calculator.

A second early electronic machine was Colossus, designed by Alan Turing for the British military in 1943. This machine played an important role in breaking codes used by the German army in World War II. Turing's main contribution to the field of computer science was the idea of the Turing machine, a mathematical formalism widely used in the study of computable functions. The existence of Colossus was kept secret until long after the war ended, and the credit due to Turing and his colleagues for designing one of the first working electronic computers was slow in coming.

 * World War II when two mathematicians Jon Von Neumann and Stanislaw Ulam were faced with the puzzling problem of behavior of neutrons. 
> Donner explication du problème.
 * Hit and trial experimentation were too costly and the problem was too complicated for analysis. Hence, the Roulette wheel technique was suggested by the mathematicians. The basic data regarding the occurrence of various events were known, into which the probabilities of separate events were merged in a step by step analysis to predict the outcome of the whole sequence of events. With the remarkable success of the techniques on neutron problem, it soon became popular and found many applications in the business and industry. Ref : [1] Robeson, J. F., and R. E. Howe (Eds.), The Logistics Handbook, Free Press, 1994.

It was a simulation of 12 hard spheres using a Monte Carlo algorithm. Computer simulation is often used as an adjunct to, or substitute for, modeling systems for which simple closed form analytic solutions are not possible. There are many types of computer simulations; the common feature they all share is the attempt to generate a sample of representative scenarios for a model in which a complete enumeration of all possible states of the model would be prohibitive or impossible. [wikipedia](http://en.wikipedia.org/wiki/Computer_simulation)

At that time the field of computing was divided into two approaches: analog and digital. Analog computers were particularly suitable for problems requiring the solution of differential equations. Analog computers used electronic DC amplifiers configured as integrators and summers with a variety of non-linear, electronic and Electro-mechanicalComponents for multiplication, division, function generation, etc. These units were manually interconnected so as to produce a system that obeyed the differential equations under study. A great deal of ingenuity was often necessary in order to produce accurate, stable solutions. The electronics used vacuum tubes (valves), as did the early digitalcomputers. The transistor was still some years in the future. Ref : [3] Mcleod, J., IIE Publication.

The first general purpose programmable electronic computer was the Electronic Numerical Integrator and Computer (ENIAC), built by J. Presper Eckert and John V. Mauchly at the University of Pennsylvania. Work began in 1943, funded by the Army Ordnance Department, which needed a way to compute ballistics during World War II. The machine wasn't completed until 1945, but then it was used extensively for calculations during the design of the hydrogen bomb. By the time it was decommissioned in 1955 it had been used for research on the design of wind tunnels, random number generators, and weather prediction. Eckert, Mauchly, and John von Neumann, a consultant to the ENIAC project, began work on a new machine before ENIAC was finished. The main contribution of EDVAC, their new project, was the notion of a stored program. There is some controversy over who deserves the credit for this idea, but none over how important the idea was to the future of general purpose computers. ENIAC was controlled by a set of external switches and dials; to change the program required physically altering the settings on these controls. These controls also limited the speed of the internal electronic operations. Through the use of a memory that was large enough to hold both instructions and data, and using the program stored in memory to control the order of arithmetic operations, EDVAC was able to run orders of magnitude faster than ENIAC. By storing instructions in the same medium as data, designers could concentrate on improving the internal structure of the machine without worrying about matching it to the speed of an external control.

Regardless of who deserves the credit for the stored program idea, the EDVAC project is significant as an example of the power of interdisciplinary projects that characterize modern computational science. By recognizing that functions, in the form of a sequence of instructions for a computer, can be encoded as numbers, the EDVAC group knew the instructions could be stored in the computer's memory along with numerical data. The notion of using numbers to represent functions was a key step used by Goedel in his incompleteness theorem in 1937, work which von Neumann, as a logician, was quite familiar with. Von Neumann's background in logic, combined with Eckert and Mauchly's electrical engineering skills, formed a very powerful interdisciplinary team.

Software technology during this period was very primitive. The first programs were written out in machine code, i.e. programmers directly wrote down the numbers that corresponded to the instructions they wanted to store in memory. By the 1950s programmers were using a symbolic notation, known as assembly language, then hand-translating the symbolic notation into machine code. Later programs known as assemblers performed the translation task.

As primitive as they were, these first electronic machines were quite useful in applied science and engineering. Atanasoff estimated that it would take eight hours to solve a set of equations with eight unknowns using a Marchant calculator, and 381 hours to solve 29 equations for 29 unknowns. The Atanasoff-Berry computer was able to complete the task in under an hour. The first problem run on the ENIAC, a numerical simulation used in the design of the hydrogen bomb, required 20 seconds, as opposed to forty hours using mechanical calculators. Eckert and Mauchly later developed what was arguably the first commercially successful computer, the UNIVAC; in 1952, 45 minutes after the polls closed and with 7% of the vote counted, UNIVAC predicted Eisenhower would defeat Stevenson with 438 electoral votes (he ended up with 442).

Second génération (1954-1962)

Important innovations in computer architecturegif included index registers for controlling loops and floating point units for calculations based on real numbers. Prior to this accessing successive elements in an array was quite tedious and often involved writing self-modifying code (programs which modified themselves as they ran; at the time viewed as a powerful application of the principle that programs and data were fundamentally the same, this practice is now frowned upon as extremely hard to debug and is impossible in most high level languages). Floating point operations were performed by libraries of software routines in early computers, but were done in hardware in second generation machines.

During this second generation many high level programming languages were introduced, including FORTRAN (1956), ALGOL (1958), and COBOL (1959). Important commercial machines of this era include the IBM 704 and its successors, the 709 and 7094. The latter introduced I/O processors for better throughput between I/O devices and main memory.

The second generation also saw the first two supercomputers designed specifically for numeric processing in scientific applications. The term ``supercomputer'' is generally reserved for a machine that is an order of magnitude more powerful than other machines of its era. Two machines of the 1950s deserve this title. The Livermore Atomic Research Computer (LARC) and the IBM 7030 (aka Stretch) were early examples of machines that overlapped memory operations with processor operations and had primitive forms of parallel processing.

Third Generation (1963-1972)

  The third generation brought huge gains in computational power. Innovations in this era include the use of integrated circuits, or ICs (semiconductor devices with several transistors built into one physical component), semiconductor memories starting to be used instead of magnetic cores, microprogramming as a technique for efficiently designing complex processors, the coming of age of pipelining and other forms of parallel processing (described in detail in Chapter CA), and the introduction of operating systems and time-sharing.

The first ICs were based on small-scale integration (SSI) circuits, which had around 10 devices per circuit (or ``chip''), and evolved to the use of medium-scale integrated (MSI) circuits, which had up to 100 devices per chip. Multilayered printed circuits were developed and core memory was replaced by faster, solid state memories. Computer designers began to take advantage of parallelism by using multiple functional units, overlapping CPU and I/O operations, and pipelining (internal parallelism) in both the instruction stream and the data stream. In 1964, Seymour Cray developed the CDC 6600, which was the first architecture to use functional parallelism. By using 10 separate functional units that could operate simultaneously and 32 independent memory banks, the CDC 6600 was able to attain a computation rate of 1 million floating point operations per second (1 Mflops). Five years later CDC released the 7600, also developed by Seymour Cray. The CDC 7600, with its pipelined functional units, is considered to be the first vector processor and was capable of executing at 10 Mflops. The IBM 360/91, released during the same period, was roughly twice as fast as the CDC 660. It employed instruction look ahead, separate floating point and integer functional units and pipelined instruction stream. The IBM 360-195 was comparable to the CDC 7600, deriving much of its performance from a very fast cache memory. The SOLOMON computer, developed by Westinghouse Corporation, and the ILLIAC IV, jointly developed by Burroughs, the Department of Defense and the University of Illinois, were representative of the first parallel computers. The Texas Instrument Advanced Scientific Computer (TI-ASC) and the STAR-100 of CDC were pipelined vector processors that demonstrated the viability of that design and set the standards for subsequent vector processors.

Early in the this third generation Cambridge and the University of London cooperated in the development of CPL (Combined Programming Language, 1963). CPL was, according to its authors, an attempt to capture only the important features of the complicated and sophisticated ALGOL. However, like ALGOL, CPL was large with many features that were hard to learn. In an attempt at further simplification, Martin Richards of Cambridge developed a subset of CPL called BCPL (Basic Computer Programming Language, 1967). In 1970 Ken Thompson of Bell Labs developed yet another simplification of CPL called simply B, in connection with an early implementation of the UNIX operating system.

Fourth Generation (1972-1984)

  The next generation of computer systems saw the use of large scale integration (LSI - 1000 devices per chip) and very large scale integration (VLSI - 100,000 devices per chip) in the construction of computing elements. At this scale entire processors will fit onto a single chip, and for simple systems the entire computer (processor, main memory, and I/O controllers) can fit on one chip. Gate delays dropped to about 1ns per gate.

Semiconductor memories replaced core memories as the main memory in most systems; until this time the use of semiconductor memory in most systems was limited to registers and cache. During this period, high speed vector processors, such as the CRAY 1, CRAY X-MP and CYBER 205 dominated the high performance computing scene. Computers with large main memory, such as the CRAY 2, began to emerge. A variety of parallel architectures began to appear; however, during this period the parallel computing efforts were of a mostly experimental nature and most computational science was carried out on vector processors. Microcomputers and workstations were introduced and saw wide use as alternatives to time-shared mainframe computers.

Developments in software include very high level languages such as FP (functional programming) and Prolog (programming in logic). These languages tend to use a declarative programming style as opposed to the imperative style of Pascal, C, FORTRAN, et al. In a declarative style, a programmer gives a mathematical specification of what should be computed, leaving many details of how it should be computed to the compiler and/or runtime system. These languages are not yet in wide use, but are very promising as notations for programs that will run on massively parallel computers (systems with over 1,000 processors). Compilers for established languages started to use sophisticated optimization techniques to improve code, and compilers for vector processors were able to vectorize simple loops (turn loops into single instructions that would initiate an operation over an entire vector).

Two important events marked the early part of the third generation: the development of the C programming language and the UNIX operating system, both at Bell Labs. In 1972, Dennis Ritchie, seeking to meet the design goals of CPL and generalize Thompson's B, developed the C language. Thompson and Ritchie then used C to write a version of UNIX for the DEC PDP-11. This C-based UNIX was soon ported to many different computers, relieving users from having to learn a new operating system each time they change computer hardware. UNIX or a derivative of UNIX is now a de facto standard on virtually every computer system.

An important event in the development of computational science was the publication of the Lax report. In 1982, the US Department of Defense (DOD) and National Science Foundation (NSF) sponsored a panel on Large Scale Computing in Science and Engineering, chaired by Peter D. Lax. The Lax Report stated that aggressive and focused foreign initiatives in high performance computing, especially in Japan, were in sharp contrast to the absence of coordinated national attention in the United States. The report noted that university researchers had inadequate access to high performance computers. One of the first and most visible of the responses to the Lax report was the establishment of the NSF supercomputing centers. Phase I on this NSF program was designed to encourage the use of high performance computing at American universities by making cycles and training on three (and later six) existing supercomputers immediately available. Following this Phase I stage, in 1984-1985 NSF provided funding for the establishment of five Phase II supercomputing centers.

The Phase II centers, located in San Diego (San Diego Supercomputing Center); Illinois (National Center for Supercomputing Applications); Pittsburgh (Pittsburgh Supercomputing Center); Cornell (Cornell Theory Center); and Princeton (John von Neumann Center), have been extremely successful at providing computing time on supercomputers to the academic community. In addition they have provided many valuable training programs and have developed several software packages that are available free of charge. These Phase II centers continue to augment the substantial high performance computing efforts at the National Laboratories, especially the Department of Energy (DOE) and NASA sites.

Fifth Generation (1984-1990)

  The development of the next generation of computer systems is characterized mainly by the acceptance of parallel processing. Until this time parallelism was limited to pipelining and vector processing, or at most to a few processors sharing jobs. The fifth generation saw the introduction of machines with hundreds of processors that could all be working on different parts of a single program. The scale of integration in semiconductors continued at an incredible pace - by 1990 it was possible to build chips with a million components - and semiconductor memories became standard on all computers.

Other new developments were the widespread use of computer networks and the increasing use of single-user workstations. Prior to 1985 large scale parallel processing was viewed as a research goal, but two systems introduced around this time are typical of the first commercial products to be based on parallel processing. The Sequent Balance 8000 connected up to 20 processors to a single shared memory module (but each processor had its own local cache). The machine was designed to compete with the DEC VAX-780 as a general purpose Unix system, with each processor working on a different user's job. However Sequent provided a library of subroutines that would allow programmers to write programs that would use more than one processor, and the machine was widely used to explore parallel algorithms and programming techniques.

The Intel iPSC-1, nicknamed ``the hypercube'', took a different approach. Instead of using one memory module, Intel connected each processor to its own memory and used a network interface to connect processors. This distributed memory architecture meant memory was no longer a bottleneck and large systems (using more processors) could be built. The largest iPSC-1 had 128 processors. Toward the end of this period a third type of parallel processor was introduced to the market. In this style of machine, known as a data-parallel or SIMD, there are several thousand very simple processors. All processors work under the direction of a single control unit; i.e. if the control unit says ``add a to b'' then all processors find their local copy of a and add it to their local copy of b. Machines in this class include the Connection Machine from Thinking Machines, Inc., and the MP-1 from MasPar, Inc.

Scientific computing in this period was still dominated by vector processing. Most manufacturers of vector processors introduced parallel models, but there were very few (two to eight) processors in this parallel machines. In the area of computer networking, both wide area network (WAN) and local area network (LAN) technology developed at a rapid pace, stimulating a transition from the traditional mainframe computing environment toward a distributed computing environment in which each user has their own workstation for relatively simple tasks (editing and compiling programs, reading mail) but sharing large, expensive resources such as file servers and supercomputers. RISC technology (a style of internal organization of the CPU) and plummeting costs for RAM brought tremendous gains in computational power of relatively low cost workstations and servers. This period also saw a marked increase in both the quality and quantity of scientific visualization. 

Sixth Generation (1990 - )

This generation is beginning with many gains in parallel computing, both in the hardware area and in improved understanding of how to develop algorithms to exploit diverse, massively parallel architectures. Parallel systems now compete with vector processors in terms of total computing power and most expect parallel systems to dominate the future.

Combinations of parallel/vector architectures are well established, and one corporation (Fujitsu) has announced plans to build a system with over 200 of its high end vector processors. Manufacturers have set themselves the goal of achieving teraflops ( 10 arithmetic operations per second) performance by the middle of the decade, and it is clear this will be obtained only by a system with a thousand processors or more. Workstation technology has continued to improve, with processor designs now using a combination of RISC, pipelining, and parallel processing. As a result it is now possible to purchase a desktop workstation for about $30,000 that has the same overall computing power (100 megaflops) as fourth generation supercomputers. This development has sparked an interest in heterogeneous computing: a program started on one workstation can find idle workstations elsewhere in the local network to run parallel subtasks.

One of the most dramatic changes in the sixth generation will be the explosive growth of wide area networking. Network bandwidth has expanded tremendously in the last few years and will continue to improve for the next several years. T1 transmission rates are now standard for regional networks, and the national ``backbone'' that interconnects regional networks uses T3. Networking technology is becoming more widespread than its original strong base in universities and government laboratories as it is rapidly finding application in K-12 education, community networks and private industry. A little over a decade after the warning voiced in the Lax report, the future of a strong computational science infrastructure is bright. The federal commitment to high performance computing has been further strengthened with the passage of two particularly significant pieces of legislation: the High Performance Computing Act of 1991, which established the High Performance Computing and Communication Program (HPCCP) and Sen. Gore's Information Infrastructure and Technology Act of 1992, which addresses a broad spectrum of issues ranging from high performance computing to expanded network access and the necessity to make leading edge technologies available to educators from kindergarten through graduate school.

The Modern High Performance Computing 
Environment

 

The first computer to be termed a ``supercomputer'' was the CDC 6600, introduced in 1966. Later model CDC 6600s had a peak performance rate of 3 million floating point operations per second, or 3 Megaflops (Mflops). Computers of the 1990s are capable of peak performance rates of one Gigaflop (one thousand Megaflops). Teraflop (one million Megaflops) performance rates are predicted by the turn of the century. Table 3 shows the peak performance rate for some representative machines. With this rapid increase in performance, it has long been recognized that the definition of the term supercomputer must be dynamic. More than just peak performance rates must be considered when designating a computer as a super computer. Other factors that must be considered include memory size and memory bandwidth.

Recently the term ``supercomputer'' has been displaced by the term ``high performance computer'' or ``high performance computing environment''. This shift in terminology has resulted from the recognition that, in a computational science setting, when real problems are being tackled (rather than just CPU benchmarks) it is the entire computing environment that must offer high performance, not just the CPU. In addition to a computer with a high computational rate and a large, fast memory, a high performance computing environment must include high speed network access, reliable and robust software and compilers, documentation and training and scientific visualization support.

In today's high performance computing environment, a computational scientist's routine activities rely heavily on the Internet. Activities include exchange of e-mail and interactive talk or chat sessions with colleagues. Heavy use is made of the ability to transfer documents such as proposals, technical papers, data sets, computer programs and images. A networked high performance computing environment provides the computational scientist access to a wide array of computer architectures and applications. Using telnet to connect to a remote computer (on which one has an account) on the Internet enables the computational scientist to use all of the computational power and software applications of that remote machine.

... et en France ?

On a vu le rôle essentiel joué par la maîtrise des techniques mécanographiques dans la constitution de l'industrie informatique. Or il se trouve qu'en France la Compagnie des machines BULL était le second constructeur mondial, juste après IBM. Ses équipements, légèrement plus chers, étaient au demeurant de qualité très supérieure.

Le virage de BULL vers l'informatique fut le fait d'une équipe de scientifiques conscients des enjeux historiques mais confrontés au type d'organisation financière de l'entreprise : vieille entreprise solide, cotée en bourse, fonctionnant en autofinancement, louant ses matériels et tirant le plus gros de ses revenus de la vente des consommables (cartes à perforer).

Le début des années 60 voit se développer de manière exponentielle l'industrie informatique bien que celle-ci reste limitée à la gestion des entreprises. Le carnet de commandes de BULL se remplit, de gros investissements sont nécessaires. Par sa structure BULL doit faire appel massivement au marché financier en ne garantissant que de faibles dividendes. Et en 1964 éclate l'« Affaire BULL ». Les investisseurs se jettent alors dans l'immobilier et abandonnent les placements industriels et les actions de BULL s'effondrent. D'autant plus qu'à la différence d'IBM, BULL avait négligé le marché des PME. Le groupe américain General Electric se propose de racheter BULL pour rattraper son retard et disposer d'un marché mondial. Quelques milieux isolés, conscients de l'importance historique de l'informatique tentent d'obtenir de l'état un sauvetage (participations, nationalisation). L'optique libérale l'emporte et la 4ème firme française (juste après les pétroliers et l'automobile) passe sous la direction incompétente de GE. Les équipes se dispersent. Certains, passionnés par les architectures multitraitement partent vers Control Data, d'autres dans des sociétés de service qui connaissent un grand développement en France. Les auteurs du Gamma 60 qui travaillaient sur une machine qui eût été concurrente du 360 partent à la Compagnie des Compteurs de Montrouge réaliser une machine appelée Pallas. En fait dorénavant et pour longtemps, IBM n'avait en face de lui aucun concurrent sérieux.

Il fallut peu de temps pour que fût prise la mesure du désastre à la suite de circonstances imprévues. Alors dirigée par de Gaulle qui pratiquait une politique d'indépendance nationale, la France voulait se doter de l'arme nucléaire afin d'échapper à la tutelle des USA. Au nom de la politique de non-prolifération, les états-Unis prirent une série de sanctions comportant l'interdiction de livrer des équipements de haute technologie à la France. Par suite de cet embargo, le gouvernement se trouva contraint de construire une industrie française de l'informatique. Il fut mis en place un « Plan Calcul » comportant la création d'e l'IRIA, grand organisme public de recherche (devenu depuis l'INRIA), d'une grande compagnie d'informatique privée mais aidée par l'état : la CII (Compagnie Internationale d'Informatique) pilotée par Thomson et la Compagnie Générale d'électricité. Bien entendu les applications militaires et scientifiques y furent privilégiées.

L'équipe qui avait conçu pour IBM la série 360 avait également travaillé pour RCA (le Spectra 70) et réalisé pour une petite compagnie californienne (Scientific Data Systems) un ordinateur de 3ème génération de très belle architecture mais sans logiciel, orienté vers les applications militaires : le Sigma 7. Un accord avec la CII permit de récupérer cette gamme de machines, étant entendu qu'il s'agissait de la munir d'un bon système d'exploitation (ce qu'en France on sait faire). Le Sigma 7 fut rebaptisé 10070 et fut le départ d'une gamme de machines appelée IRIS (IRIS 50, IRIS 80), le système d'exploitation étant baptisé SIRIS.

Par ailleurs une industrie de la mini-informatique industrielle et militaire, fortement aidée par l'état réalisa des machines concurrentes du PDP11 dont certaines (SOLAR 16 de la Télémécanique) gagnèrent d'importantes parts du marché européen.

En parallèle était lancé un projet européen qui devait devenir UNIDATA (CII, PHILIPS, SIEMENS) et était destiné à permettre dans les années 70 l'émergence d'une grande industrie informatique européenne. La répartition des tâches mettait en oeuvre les compétences des trois participants : en France la maîtrise d'oeuvre, l'architecture des machines et le logiciel, à PHILIPS la technologie électronique, à SIEMENS les périphériques mécaniques (disques, bandes, la première imprimante xérographique bien conçue, etc.).

Une utilisation ingénieuse de la microprogrammation devait permettre à cette gamme de machines de fonctionner avec les instructions machine de la série P1000 PHILIPS, des machines SIEMENS compatibles IBM 360 et des IRIS. On a souvent qualifié le projet UNIDATA d'« AIRBUS de l'Informatique ». En même temps le célèbre MITI (Ministère de la Recherche et de l'Industrie) du gouvernement japonais lançait un plan similaire (avec d'ailleurs des choix techniques très proches)

Le succès d'UNIDATA supposait des aides publiques importantes, ce qui était le cas d'ailleurs au Japon. Or l'élection présidentielle de 1974 amena au pouvoir en France un Président ultra-libéral lié de plus à certains intérêts américains. Cette modification du rapport de forces politique entraîna en 1975 une dénonciation unilatérale par la France de l'accord UNIDATA. Cette décision, maintenant en général jugée désastreuse, fut justifiée au nom du dogme de l'orthodoxie libérale. En outre la grande crise économique (qui se poursuit toujours) débutée en 1969/1970 commençait à faire sentir ses effets et aux USA, beaucoup de firmes renonçaient à l'informatique qui demandait de gros investissements sans retour rapide de profit. (XDS, RCA, General Electric, etc.)

Il se livra une sombre bataille entre les milieux gaullistes (industries d'armement et politique colbertiste) et les milieux centristes libéraux (commerce et finance internationale). pour le partage des morceaux du Plan Calcul (CII, Télémécanique). Les marchés d'état de la CII furent attribués à la firme américaine Honeywell, propriétaire de l'ex BULL. Les prototypes et dossiers de la gamme UNIDATA furent totalement détruits sous la surveillance des représentants d'Honeywell Information Systems et un accord confidentiel (maintenant connu) engageait le gouvernement français à l'abandon définitif du projet. Thomson était lésé par cet abandon. à titre de compensation on lui livra son concurrent de La Télémécanique dont ce fut l'arrêt de mort dans l'informatique.

Dans le reste de l'Europe, PHILIPS abandonna la grande informatique, SIEMENS se tourna vers le Japon qui avait, lui, mené à bien son plan informatique national et réussi à placer trois firmes au premier plan de l'informatique mondiale. On sait que FUJITSU est le second constructeur mondial, juste derrière IBM.

Références: 

 * ["Introduction to Modeling and Simulation Systems"](http://www.uh.edu/~lcr3600/simulation/historical.html)
 1
 Wilson, K. G. Basic Issues of Computational Science, presented at the International Conference In Computational Physics, Trieste, October, 1986.
 2
 Grand Challenges: High Performance Computing and Communications. The FY 1992 U.S. Research and Development Program. Supplement to the President's Fiscal Year 1992 Budget. p.7.
 3
 Swanson, C. D. Computational Science Education, Cray Research Internal Working Document, September 1994.
 4
 Decker, J.F., Johnson, G.M., Computational Science: An Assessment and Projection, Proceedings of the 2nd International Conference on Computational Physics, Beijing, September 1993, World Scientific.
 5
 Goldstine, H. The Computer from Pascal to von Neumann. Princeton University Press, 1972. [A detailed account of early developments in computing. Goldstine was himself a key figure in the ENIAC and EDVAC projects].
 6
 Hayes, J. P. Computer Architecture and Organization. McGraw-Hill, 1978. [Out of date now as a text on computer architecture, but it has a very nice section on historical computers, including details on how Babbage's machine used the method of finite differences to calculate functions].
 7
 Hodge, A. Alan Turing: The Enigma. Simon and Schuster, 1983. [A comprehensive biography of Turing; Hodge is a mathematician who provides a satisfying explanation of Turing's contributions to that field as well as his work on computers and artificial intelligence].
 8
 Slater, R. Portraits in Silicon. MIT Press, 1987. [Biographical vignettes on over 30 influential figures in computer science and the computer industry from Babbage, Turing, and von Neumann to Seymour Cray, Bill Gates, and Ross Perot].
 9
 Wilson, K. G. Grand Challenges to Computational Science. Cornell University, May 1987.

Choses à côté :

 * Supercomputer russe avec une logique ternaire : 
 * Les grandes expériences de simulation comme DEUS qui ont généré des quantités fantastiques de données
 * Les structures comme PRACE, le GENCI, FUTURGRID, GRID'5000 qui sont la pour faire avancer la science et notamment l'informatique scientifique
 * La grille européenne de calcul qui est au servir du CERN
 * Le boson de higgs qui est présent dans des quantité hallucinantes de données qui sont au CC-IN2P3 à villeurbanne

Préhistoire de l'informatique - scientifique

La révolution industrielle et ses limites : Charles BABBAGE

Le problème des tables numériques, la "Difference Engine"

Dès le XVIIIème siècle on s'est posé le problème de l'exécution d'importantes suites de calculs en vue de la réalisation de tables trigonométriques et de logarithmes qui répondaient à d'importants besoins en développement : cadastre, navigation, artillerie, statistiques, calculs d'intérêts, astronomie.

On utilisait la méthode des différences finies (développements en série & approximations successives) qui conduisait à effectuer de très grands nombres d'additions en chaîne.

Pour donner un exemple, Marie-Riche baron de PRONY, ingénieur des Ponts et Chaussées (1780) fut responsable du cadastre en 1791. Marie-Riche de PRONY eut connaissance des travaux d'Adam SMITH qui avait montré l'intérêt de la division du travail en tâches élémentaires, annonçant l'organisation du travail qui sera celle de la société industrielle du XIXème siècle. Il avait mis en place un centre de calcul de 80 personnes dans deux bâtiments séparés pour réaliser de grandes tables à 14 décimales. Le grand problème était celui des erreurs. C'est pourquoi on effectuait les calculs en double en deux lieux séparés. Ce centre fut significativement nommé « manufacture à logarithmes ».

En 1760 le grand astronome Jérôme de la LANDE avait réalisé avec 30 calculateurs une table portative à 6 décimales. Cette table fit l'objet de nombreuses réimpressions chaque fois agrémentée de nouvelles fautes. Le problème des fautes était si important que, dans la préface, on invitait les usagers à signaler à l'imprimeur les erreurs rencontrées.

En 1805, un procédé d'édition dit « stéréotype » dû à Firmin DIDOT permit de conserver les pages composées d'une édition à l'autre. Ainsi non seulement on n'introduisait plus de nouvelles fautes à chaque composition mais au contraire on supprimait d'une édition à l'autre les erreurs découvertes.

Un jeune mathématicien anglais de l'université de Cambridge, Charles BABBAGE, rendit visite au baron de Prony à Paris en 1819 et, impressionné par l'ampleur des tâches répétitives nécessaires pour la réalisation des tables, eut l'idée de réaliser un calculateur spécialisé effectuant automatiquement ce travail. Il faut savoir qu'outre son activité de mathématicien, BABBAGE était un inventeur qui exerça son talent dans des domaines variés et un sportif.

En 1820, il conçut ainsi sa " Difference Engine " ou machine à calculer selon les différences finies (nom traduit à tort en français par « machine à différences » (!?)). Dès 1813, il avait déjà envisagé l'intérêt d'une telle machine.

Il en entreprit la réalisation en 1823. Cette machine ne devait pas imprimer directement les tables mais estamper des feuilles de plomb utilisées après pour l'impression. On retrouve là le souci de préparer des clichés pour l'impression de tables numériques. Il avait été très intéressé par le procédé d'impression stéréotype de DIDOT.

La tentative de réalisation de cette machine fut une véritable épopée (problèmes d'argent, contrats mal rédigés, escroqueries, etc.). Inachevée, cette machine fut cédée en l'état à la Couronne britannique en 1843. La chose se trouve exposée au Science Museum de South Kensington à Londres.

L'idée fut reprise en 1840 par un Suédois, George SCHEUTZ (1785-1873), et menée à bien sous une forme plus simple. Le financement en avait été assuré par une souscription publique après divers refus de financement institutionnel. Achevée en 1853, la première machine fut présentée dans de nombreux pays, reçut de nombreuses récompenses en Angleterre, en France (exposition universelle de 1855) mais ne trouva acquéreur qu'aux USA pour les calculs de l'observatoire d'Albany. Elle est exposée maintenant au musée technique de la Smithsonian Institution de Washington. Une seconde machine construite en Angleterre en 1859, y trouva preneur, fut exploitée jusqu'en 1914 pour calculer des tables numériques, et se trouve maintenant au Science Museum de South Kensington.

Les progrès techniques liés au développement de la mécanographie, les importants besoins en tables numériques conduisirent à la réalisation jusqu'en 1930 de diverses machines à calculer par différences finies.

Mentionnons la réalisation très élégante faite en Suède en 1859 par Martin WIBERG (1826-1905), un inventeur universel qui exerça ses talents dans pratiquement tous les domaines et suggéra la construction d'un avion à réaction ! La machine de Wiberg se trouve au Musée Technique de Stockholm.

Citons aussi le monstre réalisé en 1876 aux USA par G.B. GRANT, les projets de Léon BOLLéE (que nous connaissons déjà) de Percy LUDGATE etc. jusqu'à la réalisation faite en 1928 à New York par W.G. ECKERT, en bricolant une tabulatrice mécanographique IBM.

L' "Analytical Engine "

Alors qu'il travaillait à la réalisation de sa "Difference Engine ", Charles BABBAGE fit en 1833 une rencontre décisive : celle d'Ada LOVELACE, née en 1815, fille de Lord BYRON et personnalité scientifique exceptionnelle. De cette amitié naquit en 1834 l'idée de génie : celle d'une machine universelle à effectuer toutes sortes de suites de calculs par simple changement d'un programme de commande modifiable : l'"Analytical Engine ".

L'idée fondamentale de cette machine consistait à utiliser le métier à tisser de Jacquard qui se programmait par cartes perforées pour commander un calculateur mécanique, lui envoyer des données, en extraire les résultats, imprimer ceux-ci à l'extérieur, etc.

à cette époque, les métiers de Jacquard se répandaient dans toute l'Europe ainsi que l'Arithmomètre de Thomas de Colmar qui était le calculateur le plus perfectionné alors en usage.

Charles BABBAGE définit toutes les fonctions nécessaires à la réalisation d'un calculateur universel : Entrées/Sorties des données et résultats, mémorisation interne, transfert des données, opérateur arithmétique, programmeur/organe de commande, en un mot TOUS les organes d'un ordinateur moderne.

La description complète de sa machine fut publiée par Ada LOVELACE en 1842 dans un article (en français) resté célèbre. Elle y disait : « la machine analytique tissera des motifs algébriques comme les métiers de Jacquard tissent des fleurs et des feuilles ». Dans cet article, Ada LOVELACE expliquait comment écrire des programmes et en outre suggérait (remarque essentielle dont on ne vit les conséquences que bien plus tard) qu'on modifie la machine pour agir sur le déroulement du programme en fonction de certains résultats.

Ada LOVELACE mourut en 1852. Il n'est pas inintéressant pour l'histoire de la pensée scientifique de savoir qu'elle s'était passionnée pour le mesmérisme qui constitue une des sources de la psychanalyse et des thérapies psycho-corporelles modernes.

Charles BABBAGE ne put pas non plus mener à bien la construction de sa nouvelle machine. Il mourut ruiné en 1871. Son fils Henry BABBAGE reprit son oeuvre et réalisa une partie de la machine en 1880. En 1888, elle put calculer et imprimer les 44 premiers multiples de p.

En 1896, il en fit don également au Science Museum de Londres et en 1906, on s'en servait pour calculer quelques tables d'astronomie. Elle s'y trouve toujours.

Les limitations fondamentales de la machine de BABBAGE

La machine analytique de BABBAGE possédait tous les organes d'un ordinateur moderne. 
Toutefois la technologie utilisée au siècle dernier en rendait la réalisation extrêmement difficile. Une machine à vapeur avait même été énvisagée pour la commander. Mais surtout elle avait un défaut structurel qu'on ne vit vraiment qu'un siècle plus tard. Et ce défaut structurel découlait des conceptions scientifiques de l'époque. Il y avait une séparation totale entre l'organe de commande : le programmeur à cartes qui contenait les ordres de commande et les autres organes et informations, en particulier les données et résultats du calcul. L'idée que les résultats de calcul puissent réagir sur la commande était alors une hérésie intellectuelle.

Aujourd'hui, et nous le verrons plus loin en étudiant l'ordinateur, on appelle machine de Babbage opposée à l'ordinateur un calculateur universel à programme externe totalement indépendant des données et résultats de calcul.

Cette idée que le résultat d'une action puisse réagir sur une commande a émergé lentement au cours du XIXème siècle. Par contre il faudra attendre le XXème siècle pour qu'on se permette de traiter automatiquement les ordres de commande comme de vulgaires données. Nous sommes là au coeur du fondement conceptuel de la révolution informationnelle.

En effet c'est en 1865 que Claude BERNARD, fondant la physiologie comme science, montre l'importance de la rétroaction comme base des phénomènes de la vie, allant même jusqu'à pressentir la psychosomatique.

Et c'est en 1859 que, selon la même démarche intellectuelle, naquit une des plus grandes inventions de l'histoire des techniques : le servomoteur de Joseph FARCOT.

Joseph FARCOT (1824-1908) était un ingénieur spécialiste des machines à vapeur. Il avait amélioré le régulateur à boules de Watt, servomécanisme empirique. Là sans doute il trouva la solution d'un grand problème : on utilisait des machines à vapeur pour faire avancer de puissants vaisseaux cuirassés. Mais on était incapable d'utiliser la force motrice de la vapeur pour positionner un gouvernail de plusieurs tonnes. On utilisait toujours des cabestans mus par des équipes de matelots ! FARCOT eut l'idée de faire commander l'action de la vapeur sur le piston du gouvernail à partir d'une information prélevée sur la position de celui-ci. Il s'agissait d'une rétroaction : l'effet réagissant sur la commande. Les cuirassés géants devinrent immédiatement maniables à l'aide d'une simple roue de commande.

En Grande Bretagne, à peu près à la même époque et pour les mêmes raisons, John Mc FARLANE GRAY inventait un dispositif similaire. Et la théorie mathématique en fut élaborée par MAXWELL en Angleterre et WISCHNEGRADSKII en Russie.

Joseph FARCOT était un ingénieur très créatif à qui on doit un grand nombre d'inventions (turbines, pompes centrifuges, etc.). En outre, républicain convaincu, il consacra les dernières années de sa vie à combattre en faveur du scrutin proportionnel (qu'il ne connut pas car il fut instauré en 1910, deux ans après sa mort).

Le servomoteur de FARCOT se trouve actuellement dans les collections du CNAM à Paris..

Bibliographie

DIDI-HUBERMAN Georges - Invention de l'hystérie - Paris, Macula, 1982.
GAY Jean-Yves - Le feedback : quelques points d'histoire - 6ème Congrès International de Cybernétique et de Systémique, Tome 1, pp.289-294 - Paris, afcet, 1984.
LIGONNIèRE Robert - Préhistoire et histoire des ordinateurs - Paris, Laffont, 1987.
SABLIèRE Jean - De l'automate à l'automatisation - Paris, Gauthier- Villars, 1966.
SMITH Adam - Recherches sur la nature et les causes de la richesse des nations - Paris, Gallimard, 1976, Folio, 1991.
STEIN Dorothy - Ada Byron, La comète et le génie - Paris, Seghers, 1990.
5

L'évolution technologique jusqu'à la synthèse de Von NEUMANN

Les avatars de la machine de Babbage

La machine analytique de Babbage ayant connu la destinée que nous avons vue, il y eut diverses autres tentatives ou projets de quelques pionniers et en particulier celle de Percy LUDGATE (1883-1922). Cet inventeur irlandais, indépendamment de BABBAGE dont il ne connut les travaux que plusieurs années après le début de son étude, conçut pendant ses moments de loisirs une machine analytique universelle dont il rédigea une description complète en 1909. Cette machine comportait des solutions techniques très originales et pour certaines fort en avance sur leur époque :

sous-programmes fonctionnels sur des cylindres-programme (comme l'automate écrivain de Jaquet-Droz) pouvant préfigurer la microprogrammation,
programmation et entrée/sortie des données sur ruban de papier perforé, la perforation des résultats permettant leur réexploitation automatique,
pilotage possible par un clavier, la suite d'opérations manuelles étant perforée sur un ruban de papier utilisable comme programme de commande pour le même calcul.
En outre, cette machine était mécaniquement simple, compacte et entraînée par un moteur électrique. Hélas Percy LUDGATE ne se préoccupa pas vraiment de la construire, ce qui est fort dommage pour l'histoire de l'informatique...

Les machines logiques à raisonner

On connait l'importance dans l'histoire des mathématiques de l'école des grands logiciens anglais du XIXème siècle (Auguste de MORGAN, George BOOLE, John VENN, Lewis CARROLL) qui fondèrent l'algèbre logique.

Un économiste, mathématicien et logicien anglais, William Stanley JEVONS (1835-1882) eut l'idée de construire une machine logique qui réalisait les opérations de l'algèbre logique binaire inventée par George BOOLE. Sa machine, appelée piano logique fut construite en 1869. Elle était uniquement destinée à l'apprentissage de l'algèbre de Boole. Les expressions logiques étaient introduites par un clavier et le résultat (vrai ou faux) était affiché.

Une autre machine logique fut construite en 1911 par un des plus féconds inventeurs de l'histoire : Leonardo TORRES Y QUEVEDO (1852-1936). Ingénieur des Ponts et Chaussées, logicien, automaticien, TORRES Y QUEVEDO fut l'auteur d'innombrables inventions et réalisations (ponts suspendus, téléfériques, funiculaires, calculateurs analogiques, télécomandes par voie hertzienne, ballons dirigeables, etc.) Il réalisa à partir de 1911 des jeux d'échecs électromécaniques qui gagnaient des fins de partie ultra-simples (une tour et un roi) face à un joueur humain.

Mais surtout TORRES Y QUEVEDO est l'auteur d'un ouvrage fondamental : le premier traité moderne sur l'automatisme (Essai sur l'automatisme, 1915). Il y décrit les fonctions les plus générales de tout automate : les organes sensoriels, les organes d'action, l'énergie d'entretien, la capacité de raisonnement. En outre, il se livre à une analyse de la machine de BABBAGE dont il montre l'intérêt et appelle à des technologies qui en permettraient la réalisation. Il semble aujourd'hui que ce texte, plus largement connu qu'on ne l'a longtemps pensé, ait joué un rôle décisif dans nombre de réalisations de notre siècle.

En 1937, Claude SHANNON, jeune et brillant spécialiste des transmissions et des systèmes de commutation travaillant au M.I.T. fit une remarque fondamentale. Il montra que les règles de l'algèbre logique à 2 états élaborée en 1847 par George BOOLE et qui étaient applicables à tout raisonnement logique étaient entièrement réalisables à l'aide de circuits à relais électriques. Cette célèbre publication (A Symbolic analysis of relays and switching circuits) fut republiée en 1938 dans les célèbres Transactions of IEE et donc très largement diffusée.

Ce jeune scientifique travaillait sous la direction de Vannevar BUSCH et Norbert WIENER. Il fit plus tard à la Bell Telephone d'autres travaux fondamentaux sur la théorie de l'information et des transmissions.

En fait, en 1886, deux logiciens et ingénieurs anglais (Charles PEIRCE et Allan MARQUAND) avaient fait la même remarque mais leurs travaux restèrent ignorés... Sans parler de Paul EHRENFEST, physicien autrichien ami d'Albert EINSTEIN en 1910.

Une conséquence fondamentale de cette découverte, c'est la possibilité de réaliser concrètement une machine exécutant toute opération logique et donc, pensait-on alors, toute opération intelligente. Si maintenant nous en connaissons les limites, il est essentiel de connaitre les fonctions élémentaires que toute technologie (mécanique, relais électriques, circuits électroniques à transistors ou à tubes, systèmes à fluides, optique, etc..) doit réaliser pour pouvoir construire tout automate logique, donc entre autres un ordinateur. à savoir :

La réunion logique (fonction ou)
L'intersection logique (fonction et)
La négation logique (fonction non)
L'irruption et les développements de la mécanographie. La carte perforée.

Indépendamment du calcul, le XIXème siècle connut un important développement des moyens mécaniques de traitement et de transmission des informations. Bien sûr tout ce qui était conçu était prolongement direct de l'action humaine. Qu'il s'agisse de la machine à écrire ou du télégraphe.

La machine à écrire connut une longue histoire depuis les premières idées de Henry MILL en 1714, et les réalisations de von KNAUS (1753), PINGERTON (1780), etc. De 1830 à 1866, des dizaines de modèles furent créés. Et en 1866, Christopher SHOLES, Carlos GLIDDEN et Samuel SOULé réalisérent aux USA la première machine à écrire moderne. La technologie des machines à écrire jouera un rôle important dans les progrès des calculatrices (mécanique de précision, commandes par touches, impression).

Le télégraphe conduisit pour la première fois à utiliser l'électricité comme support d'information, et le code créé par Samuel MORSE en 1837 fut le premier code télégraphique, ancêtre du code Baudot, puis de l'ASCII.

Et là se situe une invention fondamentale: celle de la mécanographie automatique à carte perforée.

Se posaient de plus en plus au cours du XIXème siècle des problèmes de traitements de très grandes masses d'informations diverses avec des calculs très réduits voire nuls (tris, classements, recherches, totalisations). En particulier lors des opérations de recensement.

Confrontés à des transformations profondes de population dus à des immigrations massives, les états Unis mirent en place dès 1790 une politique de recensements systématiques réguliers. Cette tâche devenait de plus en plus énorme. En 1880, le dépouillement du recensement dura 7 ans pour 50 millions d'habitants. Un jeune ingénieur, Herman HOLLERITH travaillant en 1879 comme vacataire au bureau de recensement pensa qu'une solution automatique devait pouvoir être trouvée. Plus tard, ayant ouvert une agence d'ingénierie, il s'attaqua au problème. Et en 1884, il réalisa les prototypes et prit des brevets sur ce qui était le départ d'une révolution dans le traitement des informations : la carte perforée comme support universel d'information et les équipements permettant de les lire, de les manipuler, de les trier.

Il s'agit d'un simple rectangle de carton où on fait des trous, qui peut être lu par une machine, classé, trié. HOLLERITH réalisa une poinçonneuse à main, une machine à lire et totaliser et une machine à trier. évidemment le tout était piloté à la main. Mais toutefois le succès fut immense : le recensement de 1890 (62.622.250 personnes) fut dépouillé en 6 mois.

Herman HOLLERITH fonda une société qui porta son nom, et toute une industrie se répandit dans le monde (Canada, USA, Russie, Autriche, France) avec l'émergence de firmes concurrentes :

En 1909 James POWERS (Grande Bretagne) inventa la tabulatrice qui imprimait le contenu des cartes. Sur les machines Hollerith, on devait lire les compteurs, les recopier à la main et les remettre à zéro. POWERS fonda une société qui devint SAMAS et existe toujours après divers avatars sous le nom d'ICL.
En 1919 Fredric Rosen BULL (norvégien) inventa la tabulatrice imprimante parallèle, la trieuse mécanique automatique et incorpora pour la première fois dans une machine mécanographique à cartes des fonctions élémentaires de calcul. Ses travaux furent développés en France par la firme qui porta (et porte toujours) son nom.
Nous verrons que l'industrie de la mécanographie joua un rôle essentiel dans la construction de la grande industrie informatique. Signalons simplement que la société HOLLERITH changea de nom pour devenir IBM.
Les grandes réalisations des années 40

Tant les développements techniques (relais et tubes électroniques) que les résultats de SHANNON et des besoins de très gros calculs conduisirent à la fin des années 30 à de multiples initiatives pour réaliser de grands calculateurs universels.

Nous mentionnerons les plus célèbres.

Le MARK 1, conçu en 1937 par Howard AIKEN, mathématicien à l'Université de Harvard fut un monstre légendaire. C'était une gigantesque machine de Babbage électro-mécanique à relais. Elle pesait 5 tonnes, mesurait 16 mètres de long, 2 m 60 de haut, était entraînée par un moteur de 5 chevaux, était constituée pour l'essentiel de relais décimaux. Elle était alimentée par cartes ou ruban perforés. Le projet séduisit le PDG d'IBM (Thomas WATSON) qui le finança puis à la suite d'une rupture en fit construire une version sous le nom de ASCC (Automatic Sequence Controlled Calculator). Le MARK 1, inauguré en 1944, était dépassé dès sa naissance, mais le caractère spectaculaire de cette machine fit très forte impression dans le monde entier.
La réalisation de l'ENIAC (Electronic Numerical Integrator, Analyser and Computer) fut entreprise en secret en 1943 par Presper ECKERT et John MAUCHLY à l'Université de Pennsylvanie avec la collaboration de John ATANASOFF, inventeur de nombreux circuits de calcul à tubes électroniques. Il avait réalisé en 1939 à l'Université d'Iowa le premier additionneur à tubes électroniques. L'ENIAC était aussi un monstre : 17.468 tubes électroniques et 1600 relais, 30 tonnes, 150 kWatt, plus deux puissants moteurs. Occupant 160 m2 au sol. Cette machine fut inaugurée le 15 février 1946.
Mais en 1944 avait eu lieu une rencontre historique : celle du responsable de l'ENIAC et du célèbre mathématicien John von NEUMANN (1903-1957). Invité à travailler sur l'ENIAC, von NEUMANN en fit, à partir de sa vaste culture scientifique une critique structurelle décisive. L'ENIAC, comme le MARK 1 était une machine de Babbage à programme externe. Von NEUMANN montra qu'en enregistrant le programme dans la mémoire en même temps que les données, on avait un automate qui avait les propriétés de la machine de Turing, et donc une machine algorithmique universelle.

Et alors que l'ENIAC était encore en chantier, la conception d'une machine totalement nouvelle appelée EDVAC (Electronic Discrete Variable Automatic Computer) fut entreprise sous la direction de von NEUMANN par l'équipe de l'ENIAC et fit l'objet d'une célèbre publication du 30 juin 1945. Il s'agit de la première description d'un ordinateur, qu'on appelle aussi machine de von Neumann. Comme on pensait toujours que toute opération intelligente pouvait faire l'objet d'un algorithme, on pensait avoir là la machine intelligente universelle et on appela alors partout les ordinateurs « cerveaux électroniques ».

Aux USA, eut lieu une extraordinaire et complexe bataille de brevets avec d'énormes enjeux industriels compliquée par le fait que, scientifique, von NEUMANN avait mis ses idées dans le domaine public alors qu'ECKERT et MAUCHLY voulaient en faire une exploitation commerciale. Ceci fit perdre beaucoup de temps aux USA. Les premières réalisations industrielles n'en furent faites qu'en 1951 (UNIVAC 1 et IBM 701) malgré la tentative maladroite d'IBM avec le SSEC (Selective Sequence Electronic Computer) en 1948.

Le premier ordinateur construit.

Et le premier ordinateur construit le fut en Grande Bretagne en 1947 selon les idées de John Von NEUMANN par Maurice WILKES. Connaissant parfaitement les grandes réalisations américaines et conscient de la justesse des idées de Von NEUMANN, WILKES obtint les moyens de construire à l'Université de Cambridge sous le nom d'EDSAC (Electronic Delay Storage Automatic Computer) le premier calculateur universel à programme enregistré, donc le premier ordinateur qui entra en service en 1949.

En fait dès 1946, Max NEWMAN aidé d'Alan TURING avait entrepris à l'Université de Manchester la construction du premier ordinateur, mais il ne fonctionna qu'après l'EDSAC.

Bletchley Park et Alan TURING

Il fallut attendre 1975 pour que, couverts jusque là par le secret militaire, fussent connus les importants travaux réalisés durant la guerre en Grande Bretagne. L'un des services les plus importants attendus du calcul automatique était le décryptage rapide des messages chiffrés envoyés par les ennemis en temps de guerre. L'Allemagne se trouva disposer dès 1934 d'une machine mécanique à chiffrer conçue au départ (en 1919) par un hollandais pour assurer le secret des transactions commerciales. Cette machine très ingénieuse nommée ENIGMA, unique au monde, fut bien évidemment largement utilisée par l'armée allemande. L'Allemagne l'avait retirée du marché commercial mais de rares exemplaires avaient pu être achetés en Pologne et aux USA, ce qui s'avéra précieux par la suite.

Les principes de l'ENIGMA, connus en France, permirent les premiers travaux visant à en décrypter les codes. La Pologne disposant, elle, d'une machine ENIGMA d'origine réalisa des prototypes d'une version militaire dénommée BOMBA. Lors de l'invasion de 1939, ils furent transmis à la France et à l'Angleterre. Et finalement tout se retrouva à Londres...

Et on alla chercher sur son campus le célèbre mathématicien Alan TURING qu'on installa dans un domaine ultra-secret, Bletchley Park, afin de travailler sur les problèmes stratégiques du Chiffre. Sa première mission fut évidemment de casser le code de l'ENIGMA. Il en réalisa d'abord une version ultra-perfectionnée opérationnelle en 1940.

Puis, en collaboration avec Maxwell NEWMAN, Turing construisit une série de machines permettant le décryptage automatique des milliers de messages chiffrés par les ENIGMAs en service dans les armées allemandes et qui parvenaient chaque jour à Bletchley Park.

La première série, celle des Robinson, démarra en 1942. Les Robinson faisaient usage de tubes électroniques et étaient pilotées par des rubans de papier. Il s'agissait de machines à calculer spécialisées sans mémoire interne mais à très hautes performances.

La critique des faiblesses des Robinson conduisit à la conception d'une nouvelle série de machines appelées COLOSSUS. Toute la conception fut revue à partir de l'expérience des Robinson. Le COLOSSUS I entra en service en décembre 1943. Il comportait 1500 tubes électroniques, l'entrée des données se faisait avec un lecteur de ruban perforé de papier à 5000 caractères par seconde (50 km/h). On verra que la Grande Bretagne aura longtemps une grande suprêmatie dans la technologie du ruban perforé.

Le succés du COLOSSUS I conduisit à la conception et à la construction du COLOSSUS II qui entra en service en juin 1944. Il comportait 2500 tubes, plusieurs lecteurs rapides en entrée, etc. Plusieurs dizaines en furent construits. Ces machines étaient à la fois plus ingénieuses et plus puissantes que le MARK I. Elles travaillaient en numération binaire, se programmaient par tableau de connexions pour des fonctions fréquemment utilisées, disposaient de plusieurs registres de calcul et même d'une instruction de branchement conditionnel selon l'idée qu'avait eue Ada Lovelace un siècle avant.

Il est incontestable que les discrètes réalisations de Bletchley Park étaient fort en avance sur les spectaculaires grandes machines américaines. On verra que certaines des idées et solutions techniques des COLOSSUS se retrouveront ultérieurement dans l'industrie informatique britannique.

Quant-à Alan TURING, qui était passé directement du College au campus de Cambridge, puis de celui-ci au domaine fermé de Bletchley Park, il fut enfin lâché dans la vie civile quelques années après la guerre. Poursuivi pour homosexualité par la justice britannique, il préféra se suicider le 7 juin 1954 en mangeant une pomme qu'il avait préalablement piquée au cyanure, pour éviter le sort d'Oscar Wilde.

L'aventure isolée de Konrad ZUSE

En 1936 un jeune ingénieur en aéronautique allemand, Konrad ZUSE (1910-1995), entreprit dans l'appartement de ses parents à Berlin la construction d'un calculateur universel automatique à programme externe réalisé en technologie à relais électromécaniques. Une autre particularité de cette machine était l'emploi de la numération binaire dont Zuse avait vu l'intérêt technique. Konrad Zuse connaissait les travaux de Torres y Quevedo et de Schannon mais pas ceux d'Alan Turing.

Aux prises avec l'incompréhension et les aléas de la guerre, Konrad Zuse construisit de manière quasi-artisanale entre 1937 et 1944 une série de machines électromécaniques incontestablement en avance sur toutes les autres réalisations mondiales. La plupart furent détruites lors des bombardements de la guerre. La dernière en date (V4), déménagée lors de la retraite des armées allemandes; se retrouva dans une ferme de Bavière.

Les occupants américains, qui récupéraient le potentiel scientifique et technique de l'Allemagne (en particulier dans le domaine des fusées), ne furent pas intéressés. Mais un scientifique suisse, Edouard STIEFEL, qui connaissait bien les grands travaux américains, prit contact avec Zuse et récupéra cette réalisation pour l'école Polytechnique de Zürich (ETH) où elle entra en exploitation le 11 Juillet 1950 sous le nom de Z4..

Konrad Zuse n'a ni inventé ni pressenti l'ordinateur. Mais ses réalisations, à mettre en parallèle avec le MARK1 sont antérieures et techniquement beaucoup plus élégantes. Il a été le premier constructeur d'une machine de Babbage à relais, binaire et travaillant de plus sur des nombres en virgule flottante (comme le préconisait Torres y Quevedo). Par ailleurs, il a défini sous le nom de Plankalkul une première forme de langage de programmation indépendant de la machine d'exécution.

Bibliographie

BRETON Philippe - Histoire de l'Informatique - Paris, La Découverte, 1987.
CARROLL Lewis (dessins de Max ERNST) - Logique sans peine - Paris, Hermann, 1966.
FONT Jean-Marc, QUINIOU Jean-Claude, VERROUST Gérard - Les Cerveaux non- humains / Introduction à l'Informatique - Paris, Denoël, 1970.
HODGES Andrew - Alan Turing ou l'énigme de l'intelligence - Paris, Payot, 1988.
IFRAH Georges - Histoire Universelle des Chiffres - Paris, Laffont (Bouquins), 1994.
LIGONNIèRE Robert - Préhistoire et histoire des ordinateurs - Paris, Laffont, 1987.
MOREAU René - Ainsi naquit l'informatique - Paris, Dunod, 1981.
RAMUNNI Girolamo - Louis Couffignal, un pionnier de l'informatique en France in Actes du colloque sur l'Histoire de l'Informatique en France - Grenoble, INPG, 1988.

Histoire de l'INRIA

Des balbutiements de l’informatique au règne du tout numérique, Inria c’est plus de quarante ans d’histoire liée à l'essor des sciences informatiques. Retour sur les quatre grandes périodes clés de l'histoire d'Inria.

De 1967 à 1973, l'IRIA cherche ses marques
De 1974 à 1979, le difficile mûrissement de l'Institut
De 1980 à 2000, Inria en pleine expansion
Inria en route vers le XXIe siècle
De 1967 à 1973, l'IRIA cherche ses marques
Top

La création de l'IRIA, comme celles d'autres organismes, est un symbole de la politique volontariste de la période gaullienne. La France cherchait alors à se pourvoir en technologies de pointe et des moyens pour y parvenir. La France se dotait donc d'un champion national avec la CII (Compagnie Internationale pour l'Informatique, créée en décembre 1966). Cette création faisait suite à la prise de contrôle de Bull par General Electric.  La création de l'IRIA répond aussi au souhait de développer un institut proche de l'industrie, capable d'éduquer le pays dans les sciences de l'informatique et de l'automatique.

La part recherche du plan Calcul


1967 est l'année du plan Calcul. Il comporte entre autres la création d'une Délégation à l'informatique et d'un institut confié à Michel Laudet, l'IRIA. L'IRIA est un organisme d'un genre nouveau, situé à proximité du privé, préfigurant de nouvelles relations entre le public et l'industrie. Il est conçu pour être le bras armé de la CII.

International, déjà !


L'IRIA organise dès ses débuts des conférences internationales invitant les noms qui comptent dans les domaines de l'informatique et des mathématiques appliquées. L'institut obtient rapidement une renommée internationale.La formation est une de ses priorités : des écoles d'été sont créées avec EDF et le CEA, ainsi qu'un centre de formation : le centre d'études pratiques en informatique et en automatique (CEPIA), qui aura dès la première année 5000 heures de cours à son actif.

Des débuts difficiles

En 1973, André Danzin organise l'IRIA autour du SESORI (Service de synthèse et d'orientation de la recherche en informatique dirigé par Michel Monpetit et chargé d'assurer la liaison avec le Plan calcul) et du Laboria (laboratoire de recherche en informatique et en automatique) avec Jacques-Louis Lions. Le Laboria est organisé autour de projets de recherche, avec des objectifs, des moyens propres, des chefs de projet, un échéancier de réalisation. Mais avec 80 chercheurs seulement, le Laboria est loin d'avoir une taille suffisante.

De 1974 à 1979, le difficile mûrissement de l'Institut
Top

La période 1974-1979 est à la fois celle du mûrissement et de quelques occasions perdues. Le Laboria mené par Jacques-Louis Lions acquiert une identité forte. La période giscardienne remet en cause les coopérations européennes tandis que les rigidités et le manque de moyens empêchent l'institut de pouvoir suivre un rythme rapide. La diffusion des connaissances est réelle, la réputation de l'institut a franchi les frontières, des axes à long terme sont bien définis, l'IRIA pousse vers Rennes et pense à Sophia Antipolis. Mais il peine à trouver sa place dans le contexte de la fin des années 1970.

Les missions du SESORI

Le SESORI lance de nombreux projets pilotes débouchant sur des produits utilisables dans l'industrie. Exemple : la mission pour la conception assistée et le dessin par ordinateur (MICADO) a permis de coordonner la recherche en CAO. Le SESORI est chargé de la coordination nationale sur des thèmes variés allant de la robotique à la prévention des pannes, en passant par la reconnaissance des formes, le traitement numérique des images.

Les avancées du Laboria


Au Laboria, le projet Cyclades a exploré des solutions innovantes pour réaliser un réseau d'ordinateurs, sur la base du réseau de commutation par paquets, Cigale. Des présentations en France, en Europe et aux États-Unis placent l'IRIA au premier rang mondial dans le domaine. Malgré cela le projet est suspendu en 1976. Le projet Spartacus, en lien avec l'Inserm, le CNRS et le CEA, cherche à mettre au point un dispositif permettant aux tétraplégiques de recouvrer de l'autonomie.

La vocation nationale

En 1979, la décentralisation menace l'existence de l'IRIA : il est question de le délocaliser à Sophia Antipolis ou de le fusionner avec l'IRISA de Rennes (créé avec participation de l'Iria en 1975). Finalement, Jacques-Louis Lions obtient le maintien de l'institut à Rocquencourt et celui-ci gagne son « N ». Il sera désormais l'Inria (décret du 27 décembre 1979).

De 1980 à 2000, Inria en pleine expansion
Top

La nomination de Jacques-Louis Lions à la présidence d'Inria en 1980 marque un tournant. Dans la décennie 80, l'institut, avec des moyens toujours trop « justes », construit un modèle basé sur l'excellence de ses recherches avec un soucis constant de transfert vers l'industrie (créations d'entreprises innovantes dans des secteurs stratégiques). Inria est à l'origine d'un réseau de chercheurs européens (ERCIM, European Research Consortium for Informatics and Mathematics) et joue un rôle majeur dans le développement d'Internet en Europe. Après bien des tâtonnements, Inria est désormais doté de missions claires et bénéficie d'une forte réputation internationale.

L'installation en région

Dans le cadre de la déconcentration et du développement régional, l'Instut national de recherche en informatique et en automatique a construit un maillage national complet :

Irisa puis Unité de recherche de Rennes à partir de 1975 ;
Unité de recherche Sophia Antipolis en 1983 ;
Unité de recherche Lorraine/ Loria en 1986 ;
Unité de recherche Rhône-Alpes en 1992 ;
Unité de recherche Futurs, à partir de 2003, incubant 3 futures unités à Bordeaux Lille et Saclay.
20 ans de création d'entreprises

Le transfert pour l'innovation à l'institut prend la forme de dépôts de brevets, de contrats passés avec des industriels, d'animation de Consortia, et de soutien aux entreprises innovantes. De 1984 à 2004, 80 entreprises sont créées dont 45 existent toujours. Les collaborations internationales se multiplient.

Les défis scientifiques

Des plans stratégiques à 4 ans, déclinés en contrats quadriennaux avec l'État engagent Inria sur des priorités et des performances scientifiques, d'innovation et de transfert, de niveau mondial.
Le premier plan stratégique (1994-1998) mettait l'accent sur 4 thématiques de recherche: réseaux et systèmes, génie logiciel et calcul symbolique, interaction homme-machine, images, données, connaissances, simulation et optimisation des systèmes complexes.

Inria en route vers le XXIe siècle
Top
Futurs bâtiments INRIA Bordeaux Sud-Ouest
Après avoir fêté ses 40 ans en 2007, Inria reste un institut en pleine expansion. Entre 1999 et 2009, il a doublé ses effectifs. Aux 5 centres de recherche historiques (Rocquencourt, Rennes, Sophia Antipolis, Nancy et Grenoble) se sont ajoutés ceux de Saclay, Bordeaux et Lille. Solidement ancré au sein des écosystèmes industriels et académiques locaux, Inria s'implique toujours plus dans l'espace européen de la recherche. Ouvert sur l'international, il participe au rayonnement des sciences numériques dans le monde. Convaincu que le futur de nos sociétés est numérique, Inria inscrit ses recherches au cœur des grands questionnements sociétaux actuels.

Inria contribue à la compétitivité de l'économie dans un secteur fortement créateur d'emplois. Sa politique de partenariats avec l'industrie et les PME illustre son volontarisme dans le domaine du transfert technologique.

Pour mieux diffuser l'information et les connaissances scientifiques, Inria s'engage pour l'ouverture et le partage des données. L'Institut est aussi présent sur le terrain du logiciel libre.

C'est aussi un des membres fondateur de l'Alliance des sciences et technologies du numérique (ALLISTENE) dont l'objectif est de décloisonner les relations entre acteurs de la recherche et de développer les initiatives de partenariats.

La recherche européenne

Plus de la moitié des équipes-projets Inria sont impliquées dans les programmes cadres de recherche et de développement européens (PCRDT). La Commission européenne classe l'Inria parmi les 10 premiers organismes contributeurs. Dans le cadre du 7e PCRDT,  l'Inria a contribué à  identifier 2 défis scientifiques majeurs : l'Internet du futur et le patient numérique. En 2006, l'Inria a adhéré à la Charte européenne du chercheur.

En route pour le futur

Le plan stratégique 2008-2012 dessine les objectifs scientifiques de demain, centrés sur les défis du XXIe siècle.Inria renforce et diversifie ses partenariats avec les autres disciplines scientifiques et le monde économique (partenariats stratégiques), en France et en Europe, aux Etats-Unis et avec les pays émergents (Chine, Inde, Amérique du sud, Afrique).

Encore un peut d'histoire informatique :

Hollerith dépose un brevet pour une machine à calculer automatique (1884), et fonde (1896) la société qui deviendra IBM
Construction au MIT d'un calculateur analogique (1925)
Turing propose sa définition de machine (1936), outil capital pour l'informatique théorique

L'ENIAC est construit en 1946 en partie sur les principes de von Neumann : il pèse 30 tonnes, occupe 72 m2, est équipé de 19 000 lampes.
Il calcule en décimal, repose sur des tubes à vide, et n'a pas de programmes enregistrés
C’est encore un calculateur, pas un ordinateur universel
Von Neumann définit l'architecture d'un ordinateur universel (EDVAC, 1949)

Les premiers ordinateurs
Création de la théorie de l'information (Shannon, 1948) : mesure d'une quantité d'informations en chiffres binaires (bits)
Construction du Manchester Mark I, premier ordinateur (1948) à programme enregistré

Univac, premier ordinateur commercialisé (1951) par Remington Rand (15 exemplaires vendus) ; premier ordinateur français (pour l'armée)
Premier ordinateur construit en série par IBM (1953) : 900kg, vendu $500 000 à plus de 1000 exemplaires
Invention du mot ordinateur (1955), initialement par IBM Apparition des ordinateurs à transistors (1956),
et création du premier disque dur (IBM : 1000Kg, 5 Mega) Invention du terme informatique (1962)

Le top 500 et grosso modo, les archi

As of June 2013[update], China's Tianhe-2 supercomputer is the fastest in the world at 33.86 petaFLOPS.

Systems with massive numbers of processors generally take one of two paths: In one approach (e.g., in distributed computing), a large number of discrete computers (e.g., laptops) distributed across a network (e.g., the internet) devote some or all of their time to solving a common problem; each individual computer (client) receives and completes many small tasks, reporting the results to a central server which integrates the task results from all the clients into the overall solution.[4][5] In another approach, a large number of dedicated processors are placed in close proximity to each other (e.g. in a computer cluster); this saves considerable time moving data around and makes it possible for the processors to work together (rather than on separate tasks), for example in mesh and hypercube architectures.

As the price/performance of general purpose graphic processors (GPGPUs) has improved, a number of petaflop supercomputers such as Tianhe-I and Nebulae have started to rely on them.[29] However, other systems such as the K computer continue to use conventional processors such as SPARC-based designs and the overall applicability of GPGPUs in general purpose high performance computing applications has been the subject of debate, in that while a GPGPU maybe tuned to score well on specific benchmarks its overall applicability to everyday algorithms may be limited unless significant effort is spent to tune the application towards it.[30] However, GPUs are gaining ground and in 2012 the Jaguar supercomputer was transformed into Titan by replacing CPUs with GPUs.[31][32][33]

A number of "special-purpose" systems have been designed, dedicated to a single problem. This allows the use of specially programmed FPGA chips or even custom VLSI chips, allowing better price/performance ratios by sacrificing generality. Examples of special-purpose supercomputers include Belle,[34]Deep Blue,[35] and Hydra,[36] for playing chess, Gravity Pipe for astrophysics,[37]MDGRAPE-3 for protein structure computation molecular dynamics[38] and Deep Crack,[39] for breaking the DES cipher.

In general, the speed of supercomputers is measured and benchmarked in "FLOPS" (FLoating Point Operations Per Second), and not in terms of MIPS, i.e. as "instructions per second", as is the case with general purpose computers.[69] These measurements are commonly used with an SI prefix such as tera-, combined into the shorthand "TFLOPS" (1012 FLOPS, pronounced teraflops), or peta-, combined into the shorthand "PFLOPS" (1015 FLOPS, pronounced petaflops.) "Petascale" supercomputers can process one quadrillion (1015) (1000 trillion) FLOPS. Exascale is computing performance in the exaflops range. An exaflop is one quintillion (1018) FLOPS (one million teraflops).

No single number can reflect the overall performance of a computer system, yet the goal of the Linpack benchmark is to approximate how fast the computer solves numerical problems and it is widely used in the industry.[70] The FLOPS measurement is either quoted based on the theoretical floating point performance of a processor (derived from manufacturer's processor specifications and shown as "Rpeak" in the TOP500 lists) which is generally unachievable when running real workloads, or the achievable throughput, derived from the LINPACK benchmarks and shown as "Rmax" in the TOP500 list. The LINPACK benchmark typically performs LU decomposition of a large matrix. The LINPACK performance gives some indication of performance for some real-world problems, but does not necessarily match the processing requirements of many other supercomputer workloads, which for example may require more memory bandwidth, or may require better integer computing performance, or may need a high performance I/O system to achieve high levels of performance.[70]

Ne pas oublier de citer les problèmes actuels du top500, liés à linpack, aux problèmes qu'il trouve bon et aux autres.
Pas oublier aussi de parler du fait que l'on a du GPU et rien d'autre.
> On fait quoi avec le GPU acutellement comme simulations ?

The stages of supercomputer application may be summarized in the following table:

Decade  Uses and computer involved
1970s   Weather forecasting, aerodynamic research (Cray-1).[72]
1980s   Probabilistic analysis,[73] radiation shielding modeling[74] (CDC Cyber).
1990s   Brute force code breaking (EFF DES cracker),[75]
2000s   3D nuclear test simulations as a substitute for legal conduct Nuclear Proliferation Treaty (ASCI Q).[76]
2010s   Molecular Dynamics Simulation (Tianhe-1A)[77]
The IBM Blue Gene/P computer has been used to simulate a number of artificial neurons equivalent to approximately one percent of a human cerebral cortex, containing 1.6 billion neurons with approximately 9 trillion connections. The same research group also succeeded in using a supercomputer to simulate a number of artificial neurons equivalent to the entirety of a rat's brain.[78]

Modern-day weather forecasting also relies on supercomputers. The National Oceanic and Atmospheric Administration uses supercomputers to crunch hundreds of millions of observations to help make weather forecasts more accurate.[79]

Voir l'article sur wikipedia pour de la doc et les références : http://en.wikipedia.org/wiki/Supercomputer

Mais que fait-on avec autant de puissance de calcul ?

But what the heck can you do with 88,128 parallel processors?
The short answer is: Not much. Or at least, nothing that mere mortals like you or I usually concern ourselves with. Because of the Linux OS, you wouldn’t even be able to play Crysis 2 on a supercomputer — sheesh!

For the most part, supercomputing (sometimes referred to as high performance computing or HPC) is used to model simulations or perform brute force calculations. Supercomputers are research tools. Historically (in the ’70s) this was weather forecasting and aerodynamics (planes, space craft, cars), then nuclear weapons simulations and radiation shielding modeling (the height of the Cold War in the ’80s), and in recent years the emphasis has been on cracking decryption and molecular dynamics modeling.

Let’s break down a few of these applications so you can see why they’re run on supercomputers.

With weather forecasting, it is the sheer amount of data that needs to be processed. There are hundreds of thousands of weather stations around the world, each one recording dozens of variables (wind speed/direction, temperature, humidity, pollen count). All of this data needs to be compared to last night’s data, last week’s data, and historical data, all of which must be fetched from huge memory and storage banks. Generally, most of these calculations can occur at the same time, and so massive parallelism means that weather forecasts can be produced in seconds or minutes, rather than hours.
With nuclear weapons simulation, scientists model every step that a nuclear bomb takes from storage in a silo to explosion. We’re talking about a level of simulation that models whether the heat and vibration from a transport truck can affect a nuclear missile’s control systems — but also the simulation of what actually happens when a nuke explodes. Is it better to explode it at higher altitude? What if we throw in a bit more plutonium? And so on. Again, it’s the sheer number of variables that makes massive parallelism such a boon here. One processor can work on the effects of humidity, while another can work on the fluid dynamics of fissile uranium.

Brute force decryption has fallen out of vogue in the last few years (it simply takes too long to break 256- or 512-bit encryption ciphers), but in the ’90s you could use a supercomputer to break 56-bit DES encryption in a few minutes or hours. Here, massive parallelism simply lets you try different passwords at the same time; so if a single CPU can try a thousand passwords per second, a supercomputer with 10,000 CPUs can try 10 million passwords per second. In general, though, brute force attacks take too long to be worth it — though that isn’t to say that intelligence agencies around the world don’t try (most supercomputers are state-owned, incidentally).

Finally we move on to by far the most exciting use of supercomputers (and the main reason for building new supercomputers): Molecular dynamics modeling. Basically, molecular dynamics is the simulation and analysis of the movements of atoms and molecules, and as such it covers the physical and mechanical aspects of almost everything in the known universe. To put this into perspective, Tianhe-1A, the second most powerful supercomputer in the world, ran a simulation involving 110 billion atoms through 500,000 time steps. In every one of these steps, Tianhe-1A has to analyze the relationships between each and every atom. These calculations took three hours to complete and accounted for 0.116 nanoseconds of simulated time — and this is on a computer capable of processing two quadrillion calculations per second.

The most prominent example of molecular dynamics modeling Folding@Home, a distributed computing project that tries to work out the processes behind protein folding (incorrect protein folding is believed to cause a range of diseases, including Alzheimer’s and cancers). Molecular dynamics is also used in pharmaceutical research — and indeed a lot of the world’s largest, privately-owned supercomputers are owned by Big Pharma. There has been a huge surge in molecular dynamics modeling since the completion of the first human genome project in 2000, and the many iterations since. In this area, supercomputers analyze how genes interact with one another, the effects of changing or deleting a gene, and the effect of gene therapy.
Molecular dynamics is also used to model various aspects of astronomy, including the first few seconds after the Big Bang (it’s hard to model every atom in the universe compressed into a tiny point!) and what happens when a star goes supernova. Molecular dynamics brings new levels of understanding to just about every chemistry or physics experiment, so it’s not hard to see why everyone is rushing to build peta- and exascale supercomputers.

More importantly, though, China recently unveiled Sunway, a 1-petaflops supercomputer built entirely out of homegrown ShenWei CPUs. China has repeatedly stated that it wants to lessen its reliance on Western high-technology, and Sunway is a very important step in that direction. Russia has also stated that it would like to build its own homegrown supercomputers, but so far it lacks China’s manufacturing prowess.

