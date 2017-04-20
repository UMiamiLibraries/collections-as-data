**Introduction**

This dataset contains almost 50 years of issues of _La Gaceta de la Habana_, the paper of record during the Spanish colonial occupation of Cuba in the nineteenth century. The University of Miami Libraries [Cuban Heritage Collection](http://library.miami.edu/chc/) [received funding](https://library.miami.edu/blog/2015/04/02/chc-receives-funding-to-digitize-la-gaceta-de-la-habana/) to digitize its holdings of La Gaceta in 2015.

We used optimal character recognition (OCR) to generate plain text to accompany the page scans -- and though the text for each page of the newspaper is available in our digital catalog, we wanted to make it easy for researchers to download the text in bulk for purposes of distant reading. 

The OCR is imperfect -- nineteenth century newspapers were not printed with digital humanists in mind. However, our hope is that even imperfect OCR will allow scholars to explore the newspaper and find relevant information in ways that would not otherwise be possible.

We hope to continue to improve the OCR by identifying patterns for errors that we can use a bulk find-and-replace to correct. If you notice consistent OCR errors, feel free to [let us know]('mailto:p.morgan@miami.edu') via email or GitHub issues.

There are a total of 53,903 page images contained in this dataset, and in our catalog. This means that one complex aspect of working with the data (especially in tools like AntConc) is the filename for each page of text. With this large a dataset, generating separate human-readable names would be a challenge, and could cause confusion because each object (in this case, each page of the newspaper) also has a less intelligible filename in our catalog, consisting of a repository code and a string of numbers. Those filenames, however, are searchable within our Digital Collections. If you paste a filename number (i.e. 'chc99980004460001001') into the search field, either at the [La Gaceta Collection landing page](http://merrick.library.miami.edu/cubanHeritage/cubanlaw/lagaceta.php), you'll be able to retrieve the specific page, so that you can check the OCR against the original page image. We've included a guide to our filenaming conventions below.

If you have feedback about this dataset and/or the way that it has been made available, please let us know!

**File naming conventions**

Each image has a unique file name, which provides information about its relationship to its collection and to other files in the collection.
File names consist of five component parts:

1)	Repository:	**chc**99980000010001001
2)	Collection:	chc**9998**0000010001001
3)	Object:	chc9998**000001**0001001
4)	Sequence:	chc9998000001**0001**001
5)	Detail/Format:	chc99980000010001**001**

1) Repository – three-letter code which identifies the unit within UM Libraries where the source material is housed.  The most common codes are:
asm = Special Collections
asu = University Archives
chc = Cuban Heritage Collection

2) Collection – four-digit sequence which identifies the larger collection to which the item belongs, such as a manuscript collection.  The collection number is provided by the custodial unit, and combined with the repository code, uniquely identifies each digital collection. 

For example, **asm0341** is the code for the Pan American World Airways collection in Special Collections, and **chc9998** represents the CHC Periodicals collection in the Cuban Heritage Collection.

3) Object – six-digit identifier assigned sequentially to each distinct bibliographic or intellectually discreet item. 

For example, a book has many pages, but it is one object, and therefore has one object number.

Because none of these collections contains more than 10,000 items, the object number will always begin with at least one zero.

4) Sequence – four-digit identifier assigned sequentially to each distinct page, leaf, side, or view of an object.  The order of the sequence number corresponds to the order of the pages in the original object.

For example, object chc9998000301 is a volume of a newspaper, with many pages. The first page would be assigned sequence 1 (chc9998000301**0001**…), the second page would be sequence 2 (chc9998000301**0002**…), and so on.

Because no item in these collections has more than 1,000 pages, the sequence number will always begin with at least one zero.

5) Detail/Format – three-digit sequence indicating a more specific view of an image, or a file format different from the archival standard.

For all items provided here, the detail/format number will be “001”.

**Example:**

asm03410002100016001	

1)	Repository:	**asm**03410002100016001 (Original object housed at UM Special Collections)	
2)	Collection:	asm**0341**0002100016001 (Part of collection ASM0341, Pan American World Airways Collection)
3)	Object:	asm0341**0002**100016001 (Object number 210 within this collection)
4)	Sequence:	asm0341000210**0016**001 (Page 16 within this object) 
5)	Detail/Format:	asm03410002100016**001** (Detail/format is always 001)

