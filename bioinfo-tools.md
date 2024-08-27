# What bioinformatics tools are out there?

_There are more bioinformatics tools, Horatio, than are dreamt of in your philosophy_ ~ William Shakespeare, if he were a bioinformatician

The best way to find bioinformatics tools is to comb through papers and look for the link to the software implementation. Many bioinformatics journals require the source code to be publicly available on repositories such as [GitHub](https://github.com/) and [Bitbucket](https://bitbucket.org/product/). If you are just starting out on an area, it may be helpful to first be acquainted with the lay of the land by reading survey papers.

There are dedicated repositories for bioinformatics tools such as [bio.tools](https://bio.tools/). _Nucleic Acids Research_ also publishes an annual issue on bioinformatics web servers (read the 2024 issue [here](https://academic.oup.com/nar/article/52/W1/W1/7695501)).

With the plethora of available tools, shortlisting tools can be a challenge. Here is a guide to tool selection:

-   https://davetang.org/muse/2023/07/12/deciding-which-bioinformatics-tool-to-use/

Below are some of the tools that have been used by our lab for common bioinformatics tasks. This list is only intended to be a starting point. Our understanding of life evolves, novel approaches are introduced, and new tools are developed every day.

## Sequence Alignment

-   BLAST
    -   Paper: https://www.sciencedirect.com/science/article/abs/pii/S0022283605803602
    -   Website: https://blast.ncbi.nlm.nih.gov/Blast.cgi
-   LAST
    -   Paper: https://gitlab.com/mcfrith/last/-/blob/main/doc/last-papers.rst
    -   Website: https://gitlab.com/mcfrith/last

## Sequence Clustering

-   CD-HIT
    -   Paper: https://academic.oup.com/bioinformatics/article/22/13/1658/194225
    -   Website: https://sites.google.com/view/cd-hit
-   MMseqs2
    -   Paper: https://www.nature.com/articles/nbt.3988
    -   Website: https://github.com/soedinglab/MMseqs2

## Protein Structure Prediction

-   AlphaFold

    -   Paper: https://www.nature.com/articles/s41586-021-03819-2
    -   Website: https://deepmind.google/technologies/alphafold/

-   ColabFold

    -   Paper: https://www.nature.com/articles/s41592-022-01488-1
    -   Website: https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb
    -   For local installation: https://github.com/YoshitakaMo/localcolabfold

## Protein Structure Alignment

-   US-align
    -   Paper: https://www.nature.com/articles/s41592-022-01585-1
    -   Website: https://zhanggroup.org/US-align/

## Protein Structure Searching and Clustering

-   Foldseek
    -   Paper: https://www.nature.com/articles/s41587-023-01773-0
    -   Website: https://github.com/steineggerlab/foldseek

## Sequence Collection

-   Phages
    -   INPHARED
        -   Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9041510/
        -   Website: https://github.com/RyanCook94/inphared

## Gene Prediction

-   Prokaryotes
    -   Prodigal
        -   Paper: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-11-119
        -   Website: https://github.com/hyattpd/Prodigal

## Genome Annotation

-   Viruses
    -   PHROG
        -   Paper: https://academic.oup.com/nargab/article/3/3/lqab067/6342220
        -   Website: https://phrogs.lmge.uca.fr/
