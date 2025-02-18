# A Replication of _Measuring and Explaining Political Sophistication through Textual Complexity_ (Benoit et al., 2019)

## Description

This repository includes materials to replicate key findings from **Benoit, Kenneth, Kevin Munger, and Arthur Spirling. 2019. “Measuring and Explaining Political Sophistication through Textual Complexity.” _American Journal of Political Science_ 63 (2): 491–508.doi: 10.1111/ajps.12423.** It includes links to the original paper and authors' replication materials, our replication materials, and our findings presentation and report.

## Research Goals

Benoit, Munger, and Spirling (2019) have two main goals in their paper:

1. Re-explore determinants of textual sophistication, specifically in a political context
2. Develop a model for political textual complexity that can be applied to any political text
	
## Repository Structure & File Contents

<table>
	<thead>
    		<tr>
	      		<th>Folder</th>
	      		<th>Folder Description</th>
			<th>Included File</th>
			<th>File Description</th>
    		</tr>
  	</thead>
  	<tbody>
    		<tr>
        		<td><tt>01_OriginalPaper</tt></td>
			<td>Includes readme file with link to original Benoit et al., 2019 paper </td>
			<td><tt>readme.txt</tt></td>
			<td>Links to original Benoit et al., 2019 paper</td>
    		</tr>
		<tr>
        		<td><tt>02_DataverseMaterials/dataverse_files</tt></td>
			<td>Includes readme file with link to Benoit et al.'s paper replication materials hosted on Harvard Dataverse website</td>
			<td><tt>readme.txt</tt></td>
			<td>Links to Benoit et al.'s paper replication materials hosted on Harvard Dataverse website</td>
    		</tr>
    		<tr>
        		<td rowspan="3"><tt>03_Replication</tt></td>
			<td rowspan="3">Includes Bartlett & Shi's replication materials</td>
			<td><tt>01_replicate_text_complexity.qmd</tt></td>
			<td>QMD script to replicate paper key findings</td>
    		</tr>
    		<tr>
        		</td><td><tt>01_replicate_text_complexity.html</tt></td>
			<td>HTML output from running <tt>01_replicate_text_complexity.qmd</tt> script; presents code collated alongside output</td>
		</tr>
		<tr>
        		</td><td><tt>bootstrap.css</tt></td>
			<td>CSS code called in <tt>01_replicate_text_complexity.qmd</tt> for HTML formatting in <tt>01_replicate_text_complexity.html</tt></td>
		</tr>
  		<tr>
        		<td rowspan="4"><tt>04_Presentation</tt></td>
			<td rowspan="4">Includes presentation materials</td>
			<td><tt>Bartlett-Shi-replication-1-presentation.qmd</tt></td>
			<td>QMD script to produce presentation</td>
    		</tr>
    		<tr>
        		</td><td><tt>Bartlett-Shi-replication-1-presentation.html</tt></td>
			<td>Presentation given on 2/11/25</td>
		</tr>
		<tr>
        		</td><td><tt>bootstrap.scss</tt></td>
			<td>CSS code called in <tt>Bartlett-Shi-replication-1-presentation.qmd</tt> for HTML formatting in <tt>Bartlett-Shi-replication-1-presentation.html</tt></td>
		</tr>
		<tr>
        		</td><td><tt>table1.png</tt></td>
			<td>PNG file with list of covariates screen-captured from Benoit et al., 2019 original paper (called in <tt>Bartlett-Shi-replication-1-presentation.qmd</tt>)</td>
		</tr>
  		<tr>
        		<td rowspan="2"><tt>05_FinalReport</tt></td>
			<td rowspan="2">Includes final paper materials</td>
			<td><tt>Bartlett-Shi-replication-1-paper.rmd</tt></td>
			<td>RMD script to produce <tt>Bartlett-Shi-replication-1-paper.pdf</tt></td>
    		</tr>
    		<tr>
        		</td><td><tt>Bartlett-Shi-replication-1-paper.pdf</tt></td>
			<td>Bartlett & Shi final paper</td>
		</tr>

</table>


## Code Guidance

All file path references in the QMD and RMD scripts in this repository assume that the user has cloned this repo and thus is using our same folder structure. The file path references also assume that the user has downloaded the three  replication files noted below (available on the Harvard Dataverse) and unpacked the files directly into `02_DataverseMaterials/dataverse_files`. 

Although the authors' replication package includes 33 files, only four are required to replicate our code:

1. `CF_output_f952737.csv` (Crowdflower results file 1)
2. `CF_output_f999866.csv` (Crowdflower results file 2)
3. `BT_unstructured_brT_abilities.rda` (Unstructured Bradley-Terry model results (with bias reduction))
4. `BT_unstructured_brF_abilities.rda` (Unstructured Bradley-Terry model results (no bias reduction))

We also recommend downloading `Codebook.pdf` to understand variables included in the replication files and `README.pdf` to understand the overall structure and contents of the authors' replication package.

## Authors

Maria Bartlett & Wendy Shi

## Course & Institutional Information

This project was produced as part of the spring 2025 **PPOL 6801: Text as Data: Computational Linguistics** course at **McCourt School of Public Policy** at **Georgetown University**.

## References

Benoit, Kenneth, Kevin Munger, and Arthur Spirling. 2019. “Measuring and Explaining Political Sophistication through Textual Complexity.” _American Journal of Political Science_ 63 (2): 491–508.doi: 10.1111/ajps.12423

Benoit, Kenneth, 2019, “Replication Data for: Measuring and Explaining Political Sophistication Through Textual Complexity”, https://doi.org/10.7910/DVN/9SF3TI, Harvard Dataverse, V1, UNF:6:3lWCX52gHXjVfaeDpmEBPQ== [fileUNF]
