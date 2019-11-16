# Simple Python Mail Retrieval, Analyzer, and Visualizer

> Analyzing an EMAIL Archive from gmane and vizualizing the data
using the D3 JavaScript library. This is a set of tools that allow you to pull down an archive
of a gmane repository using the instructions at:

http://gmane.org/export.php

http://mbox.dr-chuck.net/

The first step is to spider the gmane repository.  The base URL 
is hard-coded in the gmane.py and is hard-coded to the Sakai
developer list. You can spider another repository by changing that
base url. Make sure to delete the content.sqlite file if you 
switch the base url. The gmane.py file operates as a spider in 
that it runs slowly and retrieves one mail message per second so 
as to avoid getting throttled by gmane.org. It stores all of
its data in a database and can be interrupted and re-started 
as often as needed. t may take many hours to pull all the data
down.  So you may need to restart several times.

https://www.py4e.com/data_space/content.sqlite.zip

If you download this, you can "catch up with the latest" by
running gmane.py.

### Screenshots
![word](https://user-images.githubusercontent.com/13325802/68992363-02d50e80-0873-11ea-8f46-2aadaf1850b4.png)

![line](https://user-images.githubusercontent.com/13325802/68992358-f355c580-0872-11ea-955c-5217f04be024.png)
