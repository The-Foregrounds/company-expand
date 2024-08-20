This is a script to add the following company info:
- Key AI Features
- Use cases

Instructions:

1. Clone the repository:
git clone https://github.com/your-organization/company-expand.git
cd company-expand

2. Create a virtual environment:
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install dependencies:
pip install -r requirements.txt

4. Create a .env file:
cp .env.example .env

Edit the .env file and add the actual API key.

5. replace input.csv with your own company data csv (be sure to test before using the full list!). rename the uploade data 'input.csv'

6. Run the script:

python company_expand.py