# particle-swarm-optimization-python
My second repository. 

Will contain different versions of particle swarm optimization.

# simple particle swarm
This script will contain a very basic particle swarm algorithm. It will contain 2 main classes: Particle and PSO.
Particle implements a particle object. A particle has some characteristics:
- position                                                                   ( called pPosition)
- velocity                                                                   ( called pVelocity)
- inertia coefficient                                                        ( called inertia)
- sociality coefficient                                                      ( called soc)
- cognitivity coefficient                                                    ( called cog)
On top of those 5 characteristics, it also keeps in memory the following information:
- best position ever found.                                                  ( called pBestPosition)
- the value of the objective function at the best position ever found.       ( called pBestSolution)

Each particle is part of a swarm. In this simple version there is only one swarm, so every particle belongs to the same swarm.

