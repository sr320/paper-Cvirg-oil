DNA was isolated from ctendia tissue using DNAzol (Molecular Research Center, Inc) according to the manufacturer's protocol.

Genomic DNA (2750ng) was fragmented using a Bioruptor (Diagenode Inc.). Shearing was performed in 0.5μL snap cap tube, in a volume of 80μL. The DNA was sheared using the following settings: 30 cycles of 30 seconds on, 30 seconds off. Fragmentation was assessed via 1% agarose, 1x TAE gel, stained with ethidium bromide. Average fragment size was estimated to be 200bp (see GitHub repo for gel image).

Methylated DNA enrichment was performed using the MethylMiner Methylated DNA Enrichment Kit (Invitrogen) according to the manufacturer's protocol, with the following modifications. Each sample received 25μL of Dynabeads M-280 (10μg of input DNA) and 15μL of MBD-Biotin Protein (7μL/μg of input DNA). A single elution with 2000mM sodium chloride was performed. Samples were resuspended in 29μL of nuclease-free water. Samples were quantified, in duplicate, using 2.5 μL of each sample with the Quant-IT BS Kit (Invitrogen) with a FLx800 plate reader (BioTek).

Bisulfite conversion was performed using Methylamp DNA Modification Kit (Epigentek), according to the manufacturer's protocol. Samples were eluted in 10μL of Solution R6.

High-throughput sequencing libraries were constructed using the bisulfite-treated DNA from yesterday using the EpiNext Post-Bisulfite DNA Library Preparation Kit – Illumina (Epigentek). Each library received a different barcode index to facilitate multiplexed sequencing. Libraries were quantified, in duplicate, using 1.0 μL of each sample with the Quant-IT BS Kit (Invitrogen) with a FLx800 plate reader (BioTek). The libraries were pooled into a single sample, using 17ng of each library. The pooled sample was then processed to remove adaptor contamination, per the manufacturer's protcol.

This pooled sample was quantified, in duplicate using 1.0 μL of sample, with the Quant-IT BS Kit (Invitrogen) with a FLx800 plate reader (BioTek). A 10nM dilution of the pooled sample was prepared in a solution of EB Buffer (Qiagen) and 0.1% Tween 20 (final concentration; Sigma).

The multiplexed sample was sequenced at the University of Oregon Genomics & Cell Characterization Core Facility (GC3F). Sequencing was 100bp single-end, run on a HiSeq2500 (Illumina). Demultiplexing was performed by GC3F. All raw sequencing data is available in the NCBI Sequence Read Archive (SRA): SRP139854.
