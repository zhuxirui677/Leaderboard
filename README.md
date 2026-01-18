# steps for setting up-- Ashley X
cd /Users/senzu/Desktop/agnetX/Leaderboard-main
export ZHIPUAI_API_KEY="9fb98fdb2ac8473fab03614d1a220814.7kH638jBiGDmjbh0"
# docker
docker-compose down 
docker-compose pull
docker-compose up

# methods for bugs
<!-- if you successfully triggered the action(showed 🟩)
but docker didn't update
try: -->
docker-compose down
docker rmi ghcr.io/green-agent-of-legalagentbench/agent:latest
trigger
