Application Mapping Benchmark
==============

in Network On a Chip (NOC). The distance .

is a CLI software that allocates the processes on m cores 


Application mapping
=======

The mapping on 


The algorithms
=======


USAGE
===

Use the option -h to discover the usage


RTA
===

Usage rta.py:

  > python rta.py <.graphml>


LFC
===

Usage dtu_lfc.py:

  > python dtu_lcf.py  -m 5 -n 5  <.graphml>

  Example : 

  python dtu_lcf.py -m 5 -n 5 application.graphml

  The <.graphml> has to contain edges, use application.graphml as example.




Tabu Search 
===

Usage dtu_tabu.py:

  > python dtu_tabu.py -m 5 -n 5 --size_tabu 10 --global_loops 1000 --num_candidates 4 application.graphml>

  Example : 

  python dtu_tabu.py -m 5 -n 5 --size_tabu 10 --global_loops 1000 --num_candidates 4 application.graphml 


  The <.graphml> has to contain edges, use application.graphml as example.
