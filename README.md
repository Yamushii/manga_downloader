# Manga Downloader
Download Manga from mangamelon.com and compress it to .zip file (Mainly for MangaDLR - https://bitbucket.org/cylonu87/mangadlr/downloads/)

# How to Use
Install Python 3.8 or up: https://www.python.org </br>
Install Requests, shutil and BeautifulSoup4 modules </br>
<blockquote>pip install requests, shutil, beautifulsoup4</blockquote>
<h3>Usage:</h3>
<p>1. Write 'm' for whole manga (ex. https://mangamelon.com/manga/naruto) or 'c' for the chapters (ex. https://mangamelon.com/chapter/naruto/vol-72-chapter-700-1-book-of-thunder) and press enter.</p>
<p>2. If you chose whole manga, then paste link of the whole manga and press enter (example given in previous step). If you chose chapters, then paste links for one or more chapters and press enter (ex. https://mangamelon.com/chapter/naruto/vol-72-chapter-700-1-book-of-thunder;https://mangamelon.com/chapter/naruto/vol-72-chapter-700-uzumaki-naruto, <b>add ';' between the links without spaces</b>).</p>
<p>3. Paste the path to parent directory/the directory where you want to download the manga (ex. <b>[disk Letter]:\[path]\[download folder]</b>)</p>
<p>4. Write the name of the manga you want to download (ex. <b>Naruto</b>)</p>
<p>5. Write <b>Y or N</b> to choose if you want to compress downloaded chapters to .zip archives and press enter (option for MangaDLR users)</p>

# What Happens Now
<p>The program creates folder for the Manga in the parent directory and starts web-scraping/downloading.</p>
<p>It creates folder for every chapter, folders are named 1, 2, 3, ...</br>
When it finished downloading it will announce <b>Finished Downloading Process!</b></p>
<p>If you chose to create .zip files, it will create zip files named <b>[name of the manga] - Chapter [chapter number].zip</b></br>
After that finishes, it will announce <b>Finished Zipping Process!</b></p>
<p>The program has finished after announcing <b>'DONE'</b></p>
