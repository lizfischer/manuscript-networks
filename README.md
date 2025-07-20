# _Network Analysis for Book Historians_: Supplemental files

This repository houses supplemental files for the book [_Network Analysis for Book Historians: Digital Labour and Data Visualization Techniques_](https://www.arc-humanities.org/9781802702682/network-analysis-for-book-historians/) by Liz Fischer (Arc Humanities Press, 2025.)*

The book explores the potential of network analysis as a method for medieval and early modern book history. Presented through case studies of the Cotton Library, the Digital Index of Middle English Verse, and the Pforzheimer Collection, this book offers a blueprint for drawing on extant scholarly resources to visualize relationships between people, text, and books. 

I argue for considering data visualizations as their own kind of **reference works**, in the same family as traditional catalogues, editions, bibliographies, etc. Due to the restrictions of traditional publishing, the visualizations in the book are static snapshots of large, complicated networks, severely limiting the power of the visualizations to serve reference functions.

This repository houses the "raw data" for each visualization in the book, as well as the HTML & Javascript comprising interactive versions that can be downloaded and viewed locally.

For the time being, the interactive versions are also hosted online at https://manuscriptnetworks.online -- the hosted versions are linked below.

*(_Independent scholars and others without institution library access who would like to read, please contact lfischer at utexas dot edu_)

## Contents
### Digital Index of Middle English Verse
- **[_data](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/_data)** - CSVs used to load Gephi. See [DIMEV README](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/_data) for explanation of each file.
- **[text-ms](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/text-ms)** [[hosted](https://manuscriptnetworks.online/interactive/dimev/text-ms/)] - Full bi-modal network of DIMEV Texts and Manuscripts. (Figure 25)
- **[harley2253](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/harley2253)** [[hosted](https://manuscriptnetworks.online/interactive/dimev/harley2253/)]- Ego network for British Library, Harley MS 2253 within the full DIMEVtext-manuscript network. This shows the texts in Harley MS 2253, the manu-scripts that also witness those texts, and the other texts in those manuscripts. (Figure 26)
- **[text-text-deg](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/text-text-deg)** [[hosted](https://manuscriptnetworks.online/interactive/dimev/text-text-deg/)] - Network of DIMEV texts that share manuscripts,with nodes coloured by author and sized by degree. (Figure 27)
- **[text-text-btwn](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/text-text-btwn)** [[hosted](https://manuscriptnetworks.online/interactive/dimev/text-text-btwn/)] - Network of DIMEV texts that share manuscripts, withnodes coloured by author and sized by betweenness centrality. (Figure 28)
- **[subjects](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/subjects)** [[hosted](https://manuscriptnetworks.online/interactive/dimev/subjects/)] - Network of DIMEV subject labels by whether they share texts. (parent of Figure 30)
- **[oswald](https://github.com/lizfischer/manuscript-networks/tree/main/dimev/oswald)** [[hosted](https://manuscriptnetworks.online/interactive/dimev/oswald/)] - Ego network for the text “Life of St. Oswald” (DIMEV 4741) within the text-text network. (Figure 29)

### Early Borrowers of the Cotton Manuscripts
- **[_data](https://github.com/lizfischer/manuscript-networks/tree/main/cotton/_data)** - CSVs used to load Gephi. See [Cotton README](https://github.com/lizfischer/manuscript-networks/tree/main/cotton/_data) for explanation of each file.
- **[people-books](https://github.com/lizfischer/manuscript-networks/tree/main/cotton/people-books)** [[hosted](https://manuscriptnetworks.online/interactive/cotton/people-books/)] -  Network of People and Manuscripts in the Cotton loan records. (Figure 38)
- **[book-book-emperor](https://github.com/lizfischer/manuscript-networks/tree/main/cotton/book-book-emperor)** [[hosted](https://manuscriptnetworks.online/interactive/cotton/book-book-emperor/)] - Network of books in the Cotton loan records, which are connected if they were borrowed by the same person within one year of each other. Colour indicates the emperor’s name used in the manuscript’sshelfmark, which serves as a rough approximation of content similarity. (Figure 39)
- **[book-book-btwn](https://github.com/lizfischer/manuscript-networks/tree/main/cotton/book-book-btwn)** [[hosted](https://manuscriptnetworks.online/interactive/cotton/book-book-btwn/)] - Network of books in the Cotton loan records, which are connected if they were borrowed by the same person within one year of each other, sized by betweenness (Figure 40)
- **[person-person](https://github.com/lizfischer/manuscript-networks/tree/main/cotton/person-person)** [[hosted](https://manuscriptnetworks.online/interactive/cotton/person-person/)] - Network of people who borrowed the same books from Cotton’s library. (Figure 41)


### Provenance of the Pforzheimer Collection
- **[_data](https://github.com/lizfischer/manuscript-networks/tree/main/pforzheimer/_data)** - CSVs used to load Gephi. See [Pforzheimer README](https://github.com/lizfischer/manuscript-networks/tree/main/pforzheimer/_data) for explanation of each file.
- **[seller-seller](https://github.com/lizfischer/manuscript-networks/tree/main/pforzheimer/seller-seller)** [[hosted](https://manuscriptnetworks.online/interactive/pforz/seller-seller/)] - Network of provenance in the Pforzheimer collection by seller. (Figure 46)
- **[sale-sale](https://github.com/lizfischer/manuscript-networks/tree/main/pforzheimer/sale-sale)** [[hosted](https://manuscriptnetworks.online/interactive/pforz/sale-sale/)] -  Network of provenance in the Pforzheimer collection by sale rather than seller. (Figure 47)

## Using interactive visualizations
Clone this repository or download as a .zip. Open `index.html` for the visualization you wish to view.