Basic Track Hub Example
========================

Basic examples of supported file types to vizualize data in the UCSC Genome Browser using Track Hubs

File Types Featured:
- bigBed: Generated using `pybedtools <http://packages.python.org/pybedtools/>`
- bigWig: Generated using `numpy <http://docs.scipy.org/doc/numpy/reference/>`
- bam: Generated using `AriticialFastqGenerator <http://sourceforge.net/p/artfastqgen/wiki/Home/>` and `bwa <http://bio-bwa.sourceforge.net/>`

All data uses coordinates from Human CRCh37/hg19 and is randomly generated.
None of the data present should be used for analysis for biological function.

Usage
=====

1. Clone repository to server accessible to the internet
  
  git clone https://github.com/ENCODE-DCC/trackhub_example

2. Navigate to `UCSC Genome Browser <http://genome.ucsc.edu/cgi-bin/hgGateway>`

3. Click the "Click here to reset" hyperlink to reset browser to Human GRCh37/hg19 assembly

4. Click the "track hubs" button

5. On Track Hub Configuration page, click the "My Hubs" tab, and in the URL window paste path to hub.txt file
'http://path/to/trackhub_example/hub.txt" then click "Add Hub"

6. Click "Load Selected Hubs"

7. Track controls for tracks in Hub are located under header "Basic Example Hub"


