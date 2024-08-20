# Company Info Expansion Script

This script adds key information to your company data, including:

- **Key AI Features**
- **Use Cases**

## Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-organization/company-expand.git
   cd company-expand
   ```

2. **Create a Virtual Environment:**

   On macOS/Linux:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

   On Windows:
   ```bash
   python3 -m venv venv
   venv\Scripts\activate
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Create and Configure the `.env` File:**

   ```bash
   cp .env.example .env
   ```

   - Open the `.env` file and add your actual API key.

5. **Prepare Your Data:**

   - Replace the `input.csv` file with your own company data CSV.
   - Ensure to test with a small subset before using the full list.
   - Rename your uploaded data file to `input.csv`.

6. **Run the Script:**

   ```bash
   python company_expand.py
   ```
