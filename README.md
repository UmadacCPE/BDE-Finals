# BDE-Finals

Step 1: To start docker compose
docker-compose up -d --build

- verify all containers are up
docker ps

Step 3: Install dashboard.py dependencies

cd dashboard
pip install -r requirements.txt

Step 4: Launch streamlit
streamlit run dashboard.py


----- To stop the pipeline

docker-compose down

then Ctrl + C on streamlit run

Data will still be in MongoDB unless you used docker-compose down -v.
