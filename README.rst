###############
Pyodide sandbox
###############


*****
About
*****

Evaluating HTML parsing in the Browser with BeautifulSoup.


*****
Notes
*****

Run Pyodide using Docker::

	docker run -it --rm --user=root --volume=$PWD:/src iodide/pyodide-env:0.16.1 bash

::

	--publish=8000:8000
	#--user root -e NB_UID=$UID -e NB_GID=$GID \
