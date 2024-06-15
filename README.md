# azp-agent-in-docker

```bash
docker build --tag "azp-agent:linux" --file "azp-agent-linux.Dockerfile" .

docker run -it -e AZP_URL="<Azure DevOps instance>" -e AZP_TOKEN="<Personal Access Token>" -e AZP_POOL="<Agent Pool Name>" -e AZP_AGENT_NAME="Docker Agent - Linux" --name "azp-agent-linux" azp-agent:linux

```