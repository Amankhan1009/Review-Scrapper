# Myntra Review Scraper Project

## Project Detail/Summary

This project is a Myntra review scraper that allows users to extract and analyze customer reviews from the Myntra website. The scraper collects valuable information, such as product ratings, reviews, and user feedback, providing insights into customer sentiments and preferences.

## How to Setup Locally

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Amankhan1009/Review-Scrapper.git
   cd Review-Scrapper
   ```

2. Create a new conda environment and activate it
```bash
conda create -p ./env python=3.10 -y
#to activate the environment
conda activate ./env 
#or 
source activate ./env
```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Replace the environment variable in `.env` file
    Add the MongoDB environment variable in the `.env` file

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

5. Access the application in your web browser at [http://localhost:8501](http://localhost:8501).

## Dependencies

The project relies on the following dependencies:

- Streamlit: A Python library for creating interactive web applications with ease.
- MongoDB: A NoSQL database used to store and manage extracted data.
- database-connect: A package used to simplify the connection to MongoDB.

## Replacing chromedriver.exe with ChromeDriver Binary

The decision to replace `chromedriver.exe` with the `ChromeDriver binary pypi package` was made to provide better compatibility and flexibility across different operating systems. By using the binary, users can easily switch between operating systems without the need to manage different driver versions.

## MongoDB Connection

The project utilizes MongoDB as the backend database for storing scraped data. The `database-connect` package is employed to streamline the connection process, making it easier for developers to interact with MongoDB in their applications.

Feel free to explore the codebase and customize the scraper to suit your specific requirements. If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.


## Snapshots
## Example Screenshots

Below are some example screenshots of the application in action:
![Home Page](<img width="1918" height="861" alt="image" src="https://github.com/user-attachments/assets/c6dc8d4c-2ee2-43fc-b7a5-177699bdd255" />
)
![Review Extraction](<img width="1918" height="859" alt="image" src="https://github.com/user-attachments/assets/36ee92f8-3c43-4a0f-94be-9b1f25d3b37a" />
)
![Analysis](<img width="1919" height="848" alt="image" src="https://github.com/user-attachments/assets/cee9732d-34b8-48fe-ac79-b747810c6b93" />
)
![Analysis](<img width="1919" height="864" alt="image" src="https://github.com/user-attachments/assets/d9675f1d-462e-4eee-8288-57690e44c914" />
)
![Product Sections](<img width="1758" height="860" alt="image" src="https://github.com/user-attachments/assets/bf1a15bb-6363-4300-892f-631918303032" />
)

Happy scraping! 🕵️‍♂️🚀
