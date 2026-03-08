# EvenSync

A full-stack web application for discovering, creating, and managing events.

EvenSync covers the full development cycle: REST API design, user authentication,
and a dynamic React interface with advanced filtering capabilities.

---

## Features

- User authentication (register / login)
- Create, edit, and delete events
- Multi-criteria search and filtering: category, date, location, tags
- Dynamic sorting by date and price
- Full REST API consumed by the React front-end

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Back-end | Python, Flask, REST API |
| Front-end | React.js, Axios |
| Database | TinyDB |
| Versioning | Git, GitHub |

---

## Project Structure
```
EventSync/
├── backend/
│   ├── app.py
│   ├── routes/
│   ├── models/
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   └── pages/
│   └── package.json
```

---

## Installation

### Prerequisites
- Python 3.10+
- Node.js 18+

### Back-end
```bash
cd backend
pip install -r requirements.txt
flask run
```

### Front-end
```bash
cd frontend
npm install
npm start
```

Available at `http://localhost:3000`

---

## Author

**Habiba Benkemouche** — [LinkedIn](https://www.linkedin.com/in/habiba-benkemouche-56b168264) · [GitHub](https://github.com/habibabnk)
