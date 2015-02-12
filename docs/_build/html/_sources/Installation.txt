R for biologies
===============================================

Introduction
------------

This is the documentation for R for Biologies

The Tutorial
------------

Installation
------------

install R
    
Download sample file
-------------

Let's go to the working directory::

      cd /mnt
      mkdir Ecoli
      cd Ecoli
      
Download sample file::

	 curl -O https://s3.amazonaws.com/public.ged.msu.edu/ecoli_ref-5m.fastq.gz


Assemby reads
-------------

Assembling::

    /root/megahit/megahit --cpu-only -m 1e9 -l 250 -r ecoli_ref-5m.fastq.gz -o megahit_5m







And that's it!  


