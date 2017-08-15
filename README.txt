This is the record of me trying to understand the inner functionality of the PLH

1. GraphX. projects are responsible for drawing the map
2. PLHLib is the library that does all the data analysis for information coming in. 

3. ZKBDumpImporter obviously imports kill data from zkill into PLH for analysis, this seems to be a part of backend code
4. Eve Killboard Analyzer is also a part of backend code, by the looks of it. It is most likely the service that provides zkb analysis server-side.

5. LiteDB is local database storage.

6. Eve Local Chat Analyzer is the main project and runtime of the PLH.

Dev Env: Visual Studio 2017

Notes: WILL NOT COMPILE UNDER Visual Studio 2013.

All previous comments are in German, so have your google translate ready.