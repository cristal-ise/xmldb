# Implementation XMLDB module of CRISTAL-iSE kernel using eXistDB

The diagram explains the XML document structure implemented in eXistDB.
  * It is the implementation of the [cristal-ise/kernel/wiki/ClusterStorage](https://github.com/cristal-ise/kernel/wiki/ClusterStorage)
  * Each class represents an xmldb:document, the only excpetion that Item is stored as an xmldb:container. 
  * The name of the class shows how the name of the document can be constructed
  * Public attributes list the data available in different CRISTAL-iSE object (the list is not complete) 

![CRISTAL-iSE_XMLDBDocuments.puml](https://www.plantuml.com/plantuml/img/ZLJ1Rjim3BtxAmWVEyJ5haDWTEXsAD1amT9sE_IYs6mYL1ODYKeM3FltKROy9qkpvKP9Ju-FJy--yQmSXyPa7XciQj2tgi8bjief9WUMB6Pv2Bf-jjSrDKhRwrRnnkUGly_XQZ8f8R_AuKdZRa7QSk6h3JPgBbJ5LZPZSGd1nr1hVd1AcmAtQFcklkJMby0LIQU3fdtvXCvhiedhqoLS2qSjEjuNzaB9jsGCLXpRs6xSlkT_hqfnhr-msbS6YnsvrnT3k-mCst7B6JOhT5bsQvJtRx30TFejbMKvmDxMCvtUCJOZwcXy-9a1l5koqtRTnI8kLqG6bOKci5ePF41ibGcO_HgepeqIIOkY687zE7spA78yEOs32FuSgxBiyLhKFpxAqqgjrd8mB3nZEq-IOxsGUOVwOT_s-t_oCgvIP7geOfofQgCjZbJZtW6Kd5vhkuo7SIcVqnfvN3fblUQ4xMH-fTuwrWqAhcbbw7xcIyCy-0WJgB55MtiGStjeTD0I8wo8cPeFq3ggGuKrrA5xgY4UW3-m2fsorFwVd_2fvySMsdDM2ZNBqwL7bBZzBJ3UhC5loB7e0IQGY2KhdctmKVHvIo9z8bI7mVi-kvzJzmO9AJsCjg-HF-O-4ziWNijI1iNEqzitWee_nzy0)
