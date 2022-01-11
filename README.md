# SAT Competition 2022

The 2022 SAT Competition is a competitive event for solvers of the Boolean Satisfiability (SAT) problem. It is organized as a satellite event to the 25th International Conference on Theory and Applications of Satisfiability Testing and stands in the tradition of the yearly SAT Competitions, Races, and Challenges. The deadline for submitting benchmarks and solvers is Monday, February 28, 2022 (23:59 GMT -12). Visit the competition website at https://satcompetition.github.io/2022/ for details.

The area of SAT solving has seen tremendous progress over the last years. Many problems in applications such as hardware and software verification that seemed to be completely out of reach a decade ago can now be handled routinely. Besides new algorithms and better
heuristics, refined implementation techniques turned out to be vital for this success.

To keep up the driving force in improving SAT solvers, we want to motivate developers to present their work to a broader audience and to compare it with that of others.

The 2022 SAT Competition will consist of the following tracks:

* Main Track (with CaDiCaL-Hack subtrack)
* Parallel Track
* Cloud Track
* Bounded Model Checking Track (**new**)
* No-Limits Track


## Special 
### Anniversary Track: 20 Years of SAT Competition

Submissions will be run on all Application / Crafted / Main Track Instances of previous SAT competitions.


## New This Year

### Application Track: Bounded Model Checking
Apart from evaluating solvers on a broad range of benchmarks, the SAT Competition started with a track that is dedicated to a single application of SAT solvers. The application chosen for 2022 is **Bounded Model Checking**. This track includes 100 satisfiable and 100 unsatisfiable formulas of varying size and difficulty.

### Hack Track: CaDiCaL 1.4.1
In 2022 SAT Competition, we will use CaDiCaL version 1.4.1. Participants of the Main track will qualify as a CaDiCaL Hack if the diff between the patched and modified sources of CaDiCaL 1.4.1 is less than 1000 non-space characters.

### Cloud Track: Portfolios Allowed
In 2022 SAT Competition, the Portfolio Rule will *not* apply to the Cloud Track.


## Other Important Aspects

### BYOB: Bring Your Own Benchmarks
Each Main Track participant (team) is required to submit 20 new benchmark instances (not seen in previous competitions). At least 10 of those benchmarks should be "interesting": not too easy (i.e., not solved by MiniSat within one minute on modern hardware) or not too hard (unsolvable by the participant's own solver within one hour on a computer similar to the nodes of the StarExec cluster).

### PAR-2 Scoring Scheme: Penalized Average Runtime (Penalty = 2)
The solvers will be ranked based on their PAR-2 score. The score of a solver is defined to be its average runtime over all instances, whereby unsolved instances contribute twice the time limit.

### Cloud track
Amazon Web Services is enabling and sponsoring a "cloud track" for the SAT Competition in 2022. The solvers in this track will run on 100 16-core computers each with 64GB RAM that can communicate using standard protocols (ssh, MPI) with a timeout of 1000 seconds (wall-clock time) per benchmark problem. Amazon Web Services will provide $1000 in AWS credits for building and evaluating solvers, which should be more than enough for development and testing purposes. The benchmark suite will consist of hard instances, both old (unsolvable instances from prior competitions) and new ones, including formulas provided by AWS and participating teams. See https://satcompetition.github.io/2022/track_cloud.html



