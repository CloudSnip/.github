# CloudSnip - Frontend & Backend

![Minimal Modern UI](https://img.shields.io/badge/UI-Minimal%20Modern-blue) 
![Multi-Environment](https://img.shields.io/badge/Environments-Dev%20%7C%20Prod-green)

## Project Structure

```
.
├── frontend/       # React/Vue/Angular application
└── backend/        # Node.js/Spring/Django application
```

## Environments

| Environment | URL                          | Purpose          |
|-------------|------------------------------|------------------|
| Development | [dev.cloudsnip.yasuo.it](http://dev.cloudsnip.yasuo.it) | Testing & Staging |
| Production  | [cloudsnip.yasuo.it](http://cloudsnip.yasuo.it)        | Live Deployment  |

## Getting Started

### Prerequisites
- Node.js v16+
- npm/yarn

### Installation

```bash
# Clone both repositories
git clone https://github.com/CloudSnip/frontend.git
git clone https://github.com/CloudSnip/backend.git

# Install dependencies
cd frontend && npm install
cd ../backend && npm install
```

### Running Locally

```bash
# Start backend
cd backend
npm run dev

# In another terminal
cd frontend
npm run dev
```

## Features

✨ Modern UI/UX Design  
⚡ Blazing Fast Performance  
🔒 Secure Authentication  
🌐 Multi-environment Support  
📱 Responsive Design  

## Tech Stack

**Frontend:**  
<span align="center">
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind,githubactions" />
</span>

**Backend:**  
<span align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,githubactions" />
</span>

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

---

<details>
<summary>📦 Environment Variables</summary>

### Frontend
```env
VITE_BASE_URL=url_backend
```

### Backend
```env
APP_NAME=your_name

Server configuration
PORT=your_port_here
IP=your_ip_here

Security keys
MASTER_KEY=your_key
JWT_SECRET=your_jwt_secret_here

Database configuration
MONGODB_URI=url_mongo

Client URL
CLIENT_URL=url_frontend

SECRET_MASTER_URL=aws_s3_url
SECRET_MASTER_NAME=aws_s3_name

HOST=aws_host
```
</details>
