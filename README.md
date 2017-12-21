# Jupyter Datascience Notebook for R

## Run with :
	docker run -p 8888:8888 -v /path/to/data/notebooks/dir:/notebooks-dir saagie/jupyter-r-notebook:latest

	Mounting volume is optional (-v /path/to/data/notebooks/dir:/notebooks-dir) but if you want to do it:
		* create your local directory with: `mkdir -P /path/to/data/notebooks/dir`
		* make Jovyan (Jupyter notebook default user) the owner of this directory with: `chown -R 1000:100 /path/to/data/notebooks/dir`

## Libraries :

	* Data Processing
		* dplyr
		* sqldf
		* TraMiner
		* data.table

	* Machine Learning
		* arules
		* arulesSequences
		* neuralnet
		* RSNNS
		* AUC
		* recommenderlab
		* acepack
		* clv
		* cubature
		* dtw
		* ifutools
		* locpol
		* np
		* pdc
		* TSclust
		* wmtsa

	* Data Visualisation
		* shiny
		* googleVis
		* gridExtra
		* lattice
		* latticeExtra
		* misc3D
		* mvtsplot
		* TaoTeProgramming

	* Database connection
		* RImpala
		* RODBC
		* elastic
		* mongolite
		* RMySQL
		* RPostgreSQL
		* RJDBC
		* rredis
		* RCassandra
		* RNeo4j

	* Utils
		* rJava
		* foreach
		* microbenchmark
		* runit
		* Formula
		* git2r
		* gsubfn
		* hash
		* Hmisc
		* lubridate
		* longitudinal
		* miniUi
		* openssl
		* packrat
		* PKI
		* rsconnect
		* splus2R
		* withr

## Install libraries with :
	install.packages("libraryName", repos="http://cran.us.r-project.org", dependencies=TRUE)
