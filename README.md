# Vercel Telex Integration

This integration tracks vercel project deployment and server performance and sends a notification to a specified Telex.im channel.

## Features
- ✅ Extract recent deployed project detail on vercel.
- ✅ Send notification to Telex Channel.
- ✅ Easy to install.
---

##  Prerequisites
- Node.js v20.0 or latest
- Telex account
- Valid Vercel Token (for vercel rest api communication) 

## Installation

### 1️⃣ Clone the repository
```sh
git clone https://github.com/telexintegrations/telex_vercel.git
cd telex_vercel
```

### 2️⃣ Install dependencies 
```sh
pnpm install
```

### 3️⃣  Running the Application Locally
```sh
pnpm dev #app running on localhost:3000 by default
```


---

### ▶️ How to use with Telex
1. Deploy this repo to any of your favourite hosting platfrom
2. Add app on [Telex Dashboard](https://telex.im/dashboard/applications) → Add Integration
3. Enter the Integration URL:
    ```sh
    https://<domain-where-you-hosted-this-repo>/integration.json
    ```
     *ensure that GET /integration.json is returning a json object*

4. Click on 'Manage App Button' -> 
5. Click on Settings Tab; input required details (mostly the vercel token field) and save
6. Click on Output Tab, and select channels to be notified

---

## ✅ Running Tests
```sh
pnpm test
```

---


### Contributors  
📩 **Author**: [John Chioma](https://github.com/ugbewijc)  
🏢 **Organization**: [Telex.im ](https://github.com/telexintegrations/zendesk-integration)
```