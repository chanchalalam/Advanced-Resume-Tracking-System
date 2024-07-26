# Advanced-Resume-Tracking-System

This system is developed using the powerful Gemini Pro model to streamline the hiring process by analyzing job descriptions and resumes. It provides valuable insights such as job description match, missing keywords, and profile summary.

You can try it out here: https://adavanced-resume-tracking-system-app.streamlit.app

<img width="1288" alt="Screenshot 2024-06-29 at 12 21 50 AM" src="https://github.com/chanchalalam/Adavanced-Resume-Tracking-System/assets/106960500/cc7f8b1e-7b0d-465b-8874-b52435167889">

<img width="1323" alt="Screenshot 2024-06-29 at 12 24 46 AM" src="https://github.com/chanchalalam/Adavanced-Resume-Tracking-System/assets/106960500/eed57166-ef9c-4a0d-97d6-65072d66eae9">

## Features

Job Description Match: The system evaluates how well a candidate's resume matches the provided job description, helping recruiters quickly identify suitable candidates.

Missing Keywords: It identifies keywords or skills that are missing in the resume but are crucial for the job, enabling recruiters to guide candidates on enhancing their profiles.

Profile Summary: The system generates a concise profile summary highlighting key strengths and qualifications, facilitating a quick understanding of the candidate's suitability for the position.

## Requirements

1. Python 3.10
2. Stremlit
3. Gemini Pro model api key (Note: Ensure you have the necessary credentials and permissions to access the Gemini Pro API)

## Installation

1. Clone the repository: https://github.com/chanchalalam/Adavanced-Resume-Tracking-System.git
2. Install dependencies: pip install -r requirements.txt
3. Set up Gemini Pro API credentials
4. Obtain API credentials
5. Create a file named .env in the project root directory.
6. Add the following lines to .env: GOOGLE_API_KEY= "your_api_key"

   
## Usage

1. Run the application: streamlit run app.py
2. Access the application through your web browser at http://localhost:5000.
3. Input the job description and candidate's resume in the provided fields.
4. Click the "Submit" button to initiate the analysis.
5. Review the results, including the job description match, missing keywords, and profile summary.

