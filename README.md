# contentcollections-kolibri
This repository contains content collections data extracted from Kolibri content channels.


Contents:
 - `terms`: Controlled vocabularies for Kolibri ecosystem (e.g. content kinds).
 - `kolibri_db`: Tools downloading Kolibri channel databases and transforming them to JSON trees.
 - `data/kolibritreees`: Kolibri JSON tree exports for several aligned Kolibri channels.
 - `rocdata/LE/contentcollections/`: Content collections data for several aligned Kolibri channels,
   in the format ready for direct loading into ROC server.


Usage
-----

1. Export `<channelid>` as JSON source data:
   ```bash
   ./kolibri_db/reader.py --channel_id=<channelid>
   ```

2. Commit and push JSON to github.

3. Use the `ccimporter-kolibri` command in the `rocserver` instance to load the
   content collection data.



Content collections
-------------------
The following list contains various collections learning resources available from
the Kolibri Content Library that are aligned to the curriculum standards of different countries:

  - USA: The Khan Academy English Kolibri channel which contains a copy of resources from http://khanacademy.org/ 
    - [Khan Academy (English - US curriculum)](https://kolibri-catalog-en.learningequality.org/en/learn/#/topics/c9d7f950ab6b5a1199e3d6c10d7f0103) 
      channelid=`c9d7f950ab6b5a1199e3d6c10d7f0103` which contains 7260 exercises and 15255 videos.
      Last published July 7, 2020.


  - Kenya: content collections of resources aligned to the KICD curriculum standards curated by Wanjira Kinuthia:
    - [KICD Biology Curriculum (DRAFT)](https://studio.learningequality.org/channels/591b7e1bc89645ef846c1685a7dd7b50/edit/591b7e1)
      channelid=`591b7e1bc89645ef846c1685a7dd7b50`.
      Detailed curation to content list item level. Folder name N.Y refers to identifiers N.12.Y.
      Last published Jan 2020.
      See [here](http://design-sprint.learningequality.org/importcounts/591b7e1bc89645ef846c1685a7dd7b50/) for content provenance information.
    - [KICD Chemistry Curriculum (DRAFT)](https://kolibri-demo.learningequality.org/en/learn/#/topics/32b5fc156a7d46ddb8cea9663a1871be)
    	channelid=`32b5fc156a7d46ddb8cea9663a1871be`.
      Detailed curation to content list item level. Folder name N.Y refers to identifiers N.12.Y.
      Last published Jan 2020.
      See [here](http://design-sprint.learningequality.org/importcounts/32b5fc156a7d46ddb8cea9663a1871be/) for content provenance information.
    - [KICD Life Skills Curriculum (DRAFT)](https://studio.learningequality.org/channels/335b8e0ed8a3426580e4c58f62810d25/edit/335b8e0)
      channelid=`335b8e0ed8a3426580e4c58f62810d25`.
      Published Nov 2019.
      See [here](http://design-sprint.learningequality.org/importcounts/335b8e0ed8a3426580e4c58f62810d25/) for content provenance information.
      Detailed curation to subtopic level, but not many resources that match.
    - [KICD Mathematics Curriculum (DRAFT)](https://kolibri-demo.learningequality.org/en/learn/#/topics/fdab6fb66ba24d05acd011e85bdb36ba)
      channelid=`fdab6fb66ba24d05acd011e85bdb36ba`.
      Last published Apr 2020.
      Curation at topic level.
      See [here](http://design-sprint.learningequality.org/importcounts/fdab6fb66ba24d05acd011e85bdb36ba) for content provenance information.
    - [KICD Physics Curriculum (DRAFT)](https://kolibri-demo.learningequality.org/en/learn/#/topics/54aa253a3266416da0c847e16e64aa7b)	
      channelid=`54aa253a3266416da0c847e16e64aa7b`.
      Last published Jan 2020.
      Detailed curation to content list item level. Folder name N.Y refers to identifiers N.12.Y.
      See [here](http://design-sprint.learningequality.org/importcounts/54aa253a3266416da0c847e16e64aa7b/) for content provenance information.


  - Ghana: content collections aligned to the Ghana NaCCA curriculum standards:
    - Math JH 1--3, [Ghana JHS Curriculum](https://studio.learningequality.org/channels/35e861b0d611474ca169501e2bf19825/view/35e861b)
      channelid=`35e861b0d611474ca169501e2bf19825`
    - English B1--B6, JH 1--3, [Ghana English Language Curriculum](https://studio.learningequality.org/channels/2512662040d44dbf9d7ee1ba711bcf81/view/2512662)
      channelid=`2512662040d44dbf9d7ee1ba711bcf81`.
    - Our World and our People B1--B6, [Our World and Our People (Ghana)](https://studio.learningequality.org/channels/4d46c3ae62cc463ab472f0387eeb7c01/view/4d46c3a)
      channelid=`4d46c3ae62cc463ab472f0387eeb7c01`.
