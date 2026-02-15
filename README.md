 **TravelMemory**.

Create these folders:

```
TravelMemory/
│
├── docs/
│   ├── deployment.md
│   ├── screenshots/
│   └── architecture/
│
├── backend/
├── frontend/
└── README.md
```

---

# 📝 STEP 2: Add Live URL (IMPORTANT)

### Edit `README.md`

Add this at the **top**:

```md
##  Live Application

Frontend:
http://api.5souls.site/

Backend API:
http://api.5souls.site/
```

Commit this change.

---

# 📸 STEP 3: Add Deployment Documentation (With Screenshots)


### Create file:

```
docs/deployment.md
```

### Paste this TEMPLATE (you can copy-paste):

```md
# TravelMemory Deployment on AWS EC2

## 1. Infrastructure Overview
- EC2 (Ubuntu 22.04)
- Nginx (Reverse Proxy)
- Node.js (Backend)
- React (Frontend)
- MongoDB Atlas
- Application Load Balancer
- Cloudflare (DNS)

---

## 2. EC2 Setup
1. Created EC2 instance using Ubuntu AMI
2. Opened ports 22, 80, 443 in Security Group

📸 Screenshot:
![EC2 Instance](screenshots/ec2-instance.png)

---

## 3. Backend Deployment
- Cloned GitHub repository
- Installed Node.js dependencies
- Configured environment variables
- Started server using PM2

Screenshot:
![Backend Running](screenshots/backend-running.png)

---

## 4. Frontend Deployment
- Updated backend API URL
- Built React app
- Served using Nginx

Screenshot:
![Frontend Live](screenshots/frontend-live.png)

---

## 5. Scaling with Load Balancer
- Created AMI from EC2
- Launched multiple instances
- Configured Target Group and ALB

Screenshot:
![Load Balancer](screenshots/load-balancer.png)

---

## 6. Domain & Cloudflare Setup
- Domain connected to Cloudflare
- A record for frontend
- CNAME record for backend API

Screenshot:
![Cloudflare DNS](screenshots/cloudflare-dns.png)
```

---

###  What screenshots to upload

Put images inside:

```
docs/screenshots/
```

Suggested screenshots:

* EC2 instance running
* Nginx working page
* Load balancer active
* Cloudflare DNS records
* Application running in browser

---

# STEP 4: Add Architecture Diagram

### Option A (Easiest – Draw.io)

1. Open [https://draw.io](https://draw.io)
2. Create diagram using:

   * User
   * Cloudflare
   * Load Balancer
   * EC2 instances
   * Nginx
   * React
   * Node.js
   * MongoDB
3. Export as **PNG**

Save as:

```
docs/architecture/architecture.png
```


