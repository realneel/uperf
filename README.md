# Quickstart

<http://www.uperf.org> has all the latest information

On the slave run `./uperf -s`
On the master (System under test) `./uperf -m netperf.xml`

To get detailed statistics, use the `-a` option. 
	
	./uperf -m netperf.xml -a

Join <uperf-devel@lists.sourceforge.net> to discuss uperf issues.

Comments/Bugs to <realneel@gmail.com>


# Compiling the programs:

uperf uses the standard GNU build tools `(./configure;make)`

# Running the program:

1. uperf can be run as either a master(active) OR as slave(passive).
2. When run as active it needs  master flag(`-m`) with a profile describing 
   the test application. Sample profiles have been provided which are 
   sure to run, more and more application profiles are expected to be 
   added defining the various test cases.
3. When run as the slave the program needs `-s `flag
4. By default we are using `20000` port as the master port.
5. We can set the verbose level, three level are provided
	1. (`-V`) High - all the messages are printed
	2. (`-v`) med - warnings and critical messages are displayed
6. Outputs: See usage for more information

# Profile examples

Please see `workloads/sample.xml` for more details

