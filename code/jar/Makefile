all:
	hadoop jar JinYongWuxia-1.0-SNAPSHOT-jar-with-dependencies.jar /data/task2/novels task2/readnovels /data/task2/people_name_list.txt task2/pr-lpa-out
p1:
	hadoop jar JinYongWuxia-1.0-SNAPSHOT-jar-with-dependencies.jar -p1 /data/task2/novels task2/readnovels /data/task2/people_name_list.txt
p2:
	hadoop jar JinYongWuxia-1.0-SNAPSHOT-jar-with-dependencies.jar -p2 task2/readnovels/build task2/pr-lpa-out
clean:
	hdfs dfs -rm -r task2
get:
	hdfs dfs -get task2/readnovels repos
	hdfs dfs -get task2/pr-lpa-out repos
ls:
	hdfs dfs -ls task2
