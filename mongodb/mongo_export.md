mongoexport --host <>,<> \
--db <> \
--collection <> \
--username <> \
--password <> \
--authenticationDatabase <> \
--authenticationMechanism SCRAM-SHA-1 \
--query '{"created_at": {"$gte": ISODate("2016-10-30T16:59:59Z"), "$lte": ISODate("2016-10-31T16:59:59Z")}}' \
--type csv \
--fields created_at,user,global_user_id,category,behavior,target,extras,url,referer,ip,browser \
--out actions.csv