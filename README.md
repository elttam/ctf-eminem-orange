# Overview

**Title:** Eminem Orange (Tonite)   
**Category:** Web  
**Flag:** `libctf{dd6d8801-fe8f-4bfb-b9fd-d208020ea921}`  
**Difficulty:** Trivial

# Usage

The following will pull the latest 'elttam/ctf-eminem-orange' image from DockerHub, run a new container named 'libctfso-eminem-orange', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-eminem-orange \
  elttam/ctf-eminem-orange:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-eminem-orange' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-eminem-orange:latest
```