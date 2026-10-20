# Vehicle-ml: Machine Learning & Advanced Vehicle Management Dashboard

A styled Django dashboard that visualizes grouped vehicle dataset metrics, frequency tables, and charts.

## Features
- **Frequency Distribution**: Computes one-way frequency tables of vehicle manufacturers.
- **Bootstrap 5 UI**: Responsive layout featuring smooth scrollspy navigation and styled cards.
- **Plotly Integration**: Ready for advanced statistical charting and ML analytics.

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sonia-ship-it/Vehicle-ml.git
   cd Vehicle-ml
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS / Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Start development server:**
   ```bash
   python manage.py runserver
   ```
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.
