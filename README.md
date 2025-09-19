node worker.js --wtype wrk-ork-proc-aggr --env development --cluster 1

docker build -t work-ork .

docker run work-ork worker.js --wtype wrk-ork-proc-aggr --env development --cluster 1