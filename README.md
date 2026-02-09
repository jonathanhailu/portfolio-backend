# Portfolio Pro | Decoupled Full-Stack Engine

A high-performance, secure backend architecture built with **Django 6.0** and **Django REST Framework**. This service acts as the centralized "Source of Truth" for my professional portfolio, managing project metadata, blog content, and hardware-integration logs via a RESTful API.

## 🚀 Architectural Overview
- **Backend:** Django (Python 3.13)
- **API:** Django REST Framework (DRF)
- **Database:** PostgreSQL (Production) / SQLite (Development)
- **Security:** CORS-enabled with `IsAuthenticatedOrReadOnly` permission policies.
- **Image Handling:** Pillow-optimized media management.

---

## 🔧 Installation & Setup

1. **Clone & Environment:**
   ```bash
   git clone [https://github.com/jonathanhailu/portfolio-backend.git](https://github.com/jonathanhailu/portfolio-backend.git)
   cd portfolio-backend
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
