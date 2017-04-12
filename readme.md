# Brewery Directories from 1896 - 1918

The files in this repository are derived from two related New York Public Library collections, linked below.

They cover listings of breweries and maltsters in the United States from 1896 to 1918, and include fascinating location information as well as excellent historical advertising context and more.

Files come from two collections of similar titles, and the [Digital Collections](http://digitalcollections.nypl.org) links below contain all the images of the volumes held by The New York Public Library, in a variety of useful resolutions:

- [Tovey's official brewers' and maltsters' directory of the United States and Canada](http://digitalcollections.nypl.org/collections/toveys-official-brewers-and-maltsters-directory-of-the-united-states-and-canada#/?tab=navigation)
- [Brewers' guide for the United States, Canada and Mexico containing complete lists of brewers, maltsters and kindred trade](http://digitalcollections.nypl.org/collections/brewers-guide-for-the-united-states-canada-and-mexico-containing-complete-lists#/?tab=about)



## Files
Each folder in this repository represents one volume of the brewery guides.
Within each folder you'll find four things:
- A searchable PDF of the original volume;
- A `.txt` file that is the concatenated output of the 'txt' folder;
- A `_with_layout.txt` file that is the txt output of the PDF file using `pdftotxt` with the `-layout` flag;
- A 'txt' folder with all of the raw OCR txt for each page, with sequence and image ID information embedded in the filename;
- An 'hocr' folder with all of the coordinate hocr files for each page, with sequence and image ID information embedded in the filename 

### Full-Text PDFs

N.B. These are 14-26mb files

- [1896](https://github.com/hadro/brewery-guides/raw/master/1896/1896.pdf)
- [1898](https://github.com/hadro/brewery-guides/raw/master/1898/1898.pdf)
- [1899](https://github.com/hadro/brewery-guides/raw/master/1899/1899.pdf)
- [1903](https://github.com/hadro/brewery-guides/raw/master/1903/1903.pdf)
- [1904](https://github.com/hadro/brewery-guides/raw/master/1904/1904.pdf)
- [1906](https://github.com/hadro/brewery-guides/raw/master/1906/1906.pdf)
- [1913](https://github.com/hadro/brewery-guides/raw/master/1913/1913.pdf)
- [1914](https://github.com/hadro/brewery-guides/raw/master/1914/1914.pdf)
- [1915](https://github.com/hadro/brewery-guides/raw/master/1915/1915.pdf)
- [1916](https://github.com/hadro/brewery-guides/raw/master/1916/1916.pdf)
- [1917](https://github.com/hadro/brewery-guides/raw/master/1917/1917.pdf)
- [1918](https://github.com/hadro/brewery-guides/raw/master/1918/1918.pdf)

## More fun with Public Domain materials

The images and the data that allowed me to pull down these volumes from The New York Public Library's Digital Collections are all contained in the [Public Domain release](http://publicdomain.nypl.org/) NYPL put out in January 2016. (disclosure: I co-led that project as an NYPL staffer, and remain very proud of it!) If you want to play with the data and utilities yourself, there's a great [NYPL Public Domain Github repo](https://github.com/NYPL-publicdomain/data-and-utilities) waiting for you.

## License
All materials in these two collections are in the public domain according to rights analysis by the NYPL Copyright and Information Policy group. As a result, all the data and PDFs in this repo are likewise in the public domain. A CC0 license has been applied to this repo -- in the off chance that someone believes new copyright could attach to these images or the files, they are hereby released CC0 (even though they don't need to be by virtue of being public domain in the first place).
