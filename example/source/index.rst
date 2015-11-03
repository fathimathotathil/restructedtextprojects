.. example Documentation master file.

#######################
Metadata mapping in TMS
#######################

.. toctree::
   :maxdepth: 2
   
   

Schedule Files from Gracenote
=============================

The schedule files provide schedule data for programming sources for a period of 14 days or less from the date specified in the start attribute. 
For example, if the start attribute says <start>2015-10-20T00:00:00</start>, then schedule data for 14 days (till November 2, 2015) will be available in that particular file. Almost every day a new schedule file is uploaded and also there may be multiple schedule updates every day in all the markets.
Schedules are grouped by programming sources. Each source has multiple events (TV/movie broadcast is an <event>). Every event contains atleast the TMSId of the program and date and time of broadcast in GMT.  An event also provides other optional information specific to the TV program like:
•  Duration – Total Duration of the Event = Actual Content duration + duration for ads.
•  Dubbed – True if the program has been dubbed and into which language. 
•  Subtitled – True if the program has been subtitled.
•  SAP – True if SAP is available and in which language.
•  TvRating – the program’s parental rating.
•  TvSubRating – More ratings if available.
•  PartNum – if the program is available in parts.  
•  NetSynSource - Originating syndicate source of the program.
•  NetSynType – type of program syndication.
•  Qualifiers (quals) – qualifier for the program such as cc, stereo, live, new etc.
