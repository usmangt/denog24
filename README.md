# DENOG 16 (2024) Workshop - Part 1


The aim of this workshop is to provide a hands-on experience with Grafana and how to use along with Loki and Prometheus. The environment is Docker based.

## Prerequisites
- Docker
- Docker Compose
- Git

## Running the Demo

### Step 1: Clone the repository
```bash
git clone 
```

### Step 2: Deploy the monitoring stack
```bash
cd grafana-beginner
docker compose up -d
```

### Step 3: Access Grafana Web UI
Open your browser and go to `http://YOUR-IP:3000`. This should show you the Web UI. 

Login as `admin` for both username and passowd.


### Step 3: Bringing down the deployment

```bash
docker compose down
```
