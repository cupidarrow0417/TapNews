# week8
+ Juptier
+ generate model
+ server
+ newsdeduper  

## generate model
python news_class_trainer.py

## Notes
mongodb
```
mongoexport --db <database-name> --collection <collection-name> --out output.json

mongoimport --db <database-name> --collection <collection-name> --file input.json

mongoexport --db tap-news --collection news-test --out output.json

mongoimport --db tap-news --collection news-test --file output.json


db["news-test"].find().count()

tap-news news-test
```

sudo pip install tensorflow
sudo pip install watchdog
server/$ python server.js

Run backfill_class.py only add topic in MongoDB without topic
python backfill_class.py 

+ Must reading Stanford Deep learning class
+ Must reading Doc of TensorFlow

### QA

Design Doc

Very important in industrial company

Almost all feature is in Design Doc

Since, Team work in different group, like all sorts of API

Responsibility of Design Doc, which is reviewed by other group members

SOA  web server backend recommendation system

each components commuincation by API