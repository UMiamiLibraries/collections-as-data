This dataset contains short newsletters created and published by Pan American World Airways for use in classroom settings. There are two main series. "Pan American World Airways Teacher" was published quarterly, and contained collections of stories about various locations that the airline included in its itineraries. "By Flying Clipper..." collected stories related to a particular location (featured locations include Alaska, Germany, Japan, and Peru.)

This release includes Vols. 4-15 of Pan American World Airways Teacher (1948-1959), and thirteen of the "By Flying Clipper" series, also published during the 1950s. In total, there are 910 pages of text available for download. We have also included a file roster in CSV format, listing each file ID along with its metatdata.

**Potential Starting Points**

If you're new to text mining or distant reading, [Heather Froehlich's AntConc tutorial at the Programming Historian](https://programminghistorian.org/en/lessons/corpus-analysis-with-antconc) is an excellent introduction.

This release of periodicals provides opportunities to see what Pan Am writers (and implicitly, their readers) thought of as innovative technological breakthroughs. Try looking for terms like "new" and "modern," or "hours", "miles", or "distance" to find mentions of the faster travel times that Pan Am made possible.

The Pan Am World Airways Teacher series also provides a glimpse into travel and tourism-oriented discourse about culture, with potential to illuminate examples of colonial discourse, and discourse that constructs (white) American and European characteristics. Try looking at the collocates (terms that appear in close proximity to a given word) for "men" and "women", as well as for terms like "culture"/"cultural", and "eastern", "oriental", "western", and "native". Descriptors such as "european" and "south american" may also be illuminating -- though searching for "american" returns results involving "pan american airlines", rather than specifically about American culture. Using "americans" may be a more effective way to examine content that is about American travelers and tourists. Likewise, it may be interesting to explore the collocates associated with different countries or continents (i.e. Africa vs. Europe).

Finally, adjectives that imply value judgments can often be useful starting points to understand how societies and cultures were being constructed for various audiences (in this case, for children). Look for terms like "exciting", "serious", "dignified", "friendly", "happy", "sad", etc. In this regard, the Kwic (keyword in context) sorting available in AntConc's Concordance view may be useful, since it allows users to see who is being portrayed as happy, friendly, etc.

**Data Creation Process**

We used optical character recognition (OCR) to generate plain text to accompany the page scans -- and though the text for each page of the newsletters is available in our [Digital Collections](https://merrick.library.miami.edu/), we wanted to make it easy for researchers to download the text in bulk for purposes of distant reading.

The OCR in this dataset is fairly clear, though if you notice consistent errors that could be effectively corrected in bulk, you are welcome to alert us.

One complex aspect of working with this data (especially in tools like [AntConc](http://www.laurenceanthony.net/software/antconc/)) is the filename for each page of text. With larger text corpora, generating separate human-readable names would be a challenge, and could cause confusion because each object (in this case, each page of each newsletter) also has a less intelligible filename in our catalog, consisting of a repository code and a string of numbers. Those filenames, however, are searchable within our [Digital Collections](https://merrick.library.miami.edu/). If you paste a filename number (i.e. 'chc99980004460001001') into the search field, either at the [Pan American Airways Collection landing page](https://merrick.library.miami.edu/specialCollections/asm0341/), you'll be able to retrieve the specific page, so that you can check the OCR against the original page image. We've included a guide to our filenaming conventions below.

If you have feedback about this dataset and/or the way that it has been made available, please let us know! This is our second release in our Collections as Data project -- we plan to continue improving this dataset (and to release others) in the future, and we are happy to have feedback that might shape our practices and workflows.

**File naming conventions**

Each image has a unique file name, which provides information about its relationship to its collection and to other files in the collection. File names consist of five component parts:

Repository:	chc99980000010001001
Collection:	chc99980000010001001
Object:	chc99980000010001001
Sequence:	chc99980000010001001
Detail/Format:	chc99980000010001001
Each part of the file name provides information about the file:

Repository – three-letter code which identifies the unit within UM Libraries where the source material is housed. The most common codes are: asm = Special Collections, asu = University Archives, chc = Cuban Heritage Collection

Collection – four-digit sequence which identifies the larger collection to which the item belongs, such as a manuscript collection. The collection number is provided by the custodial unit, and combined with the repository code, uniquely identifies each digital collection.

For example, asm0341 is the code for the Pan American World Airways collection in Special Collections, and chc9998 represents the CHC Periodicals collection in the Cuban Heritage Collection.

Object – six-digit identifier assigned sequentially to each distinct bibliographic or intellectually discreet item.
For example, a book has many pages, but it is one object, and therefore has one object number.

Because none of these collections contains more than 10,000 items, the object number will always begin with at least one zero.

Sequence – four-digit identifier assigned sequentially to each distinct page, leaf, side, or view of an object. The order of the sequence number corresponds to the order of the pages in the original object.
For example, object chc9998000301 is a volume of a newspaper, with many pages. The first page would be assigned sequence 1 (chc99980003010001…), the second page would be sequence 2 (chc99980003010002…), and so on.

Because no item in these collections has more than 1,000 pages, the sequence number will always begin with at least one zero.

Detail/Format – three-digit sequence indicating a more specific view of an image, or a file format different from the archival standard.
For all items provided here, the detail/format number will be “001”.

Example:

asm03410002100016001

Repository:	asm03410002100016001 (Original object housed at UM Special Collections)
Collection:	asm03410002100016001 (Part of collection ASM0341, Pan American World Airways Collection)
Object:	asm03410002100016001 (Object number 210 within this collection)
Sequence:	asm03410002100016001 (Page 16 within this object)
Detail/Format:	asm03410002100016001 (Detail/format is always 001)
