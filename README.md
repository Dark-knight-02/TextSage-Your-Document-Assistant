# TextSage

TextSage is a cutting-edge tool designed to enhance text processing and analysis capabilities by leveraging advanced machine learning models and frameworks.

![TextSage Interface](https://github.com/Dark-knight-02/TextSage-Your-Document-Assistant/blob/main/media/Coverpage.png)

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Setup](#setup)
- [Running the Application](#running-the-application)
  - [Prerequisites](#prerequisites)
  - [Steps to Run](#steps-to-run)
  - [Accessing the Application](#accessing-the-application)
- [Demonstrations](#demonstrations)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)

## Technologies Used

TextSage utilizes the following technologies:
- **Python 3.9.6**: For writing and executing the core application.
- **Streamlit**: To create a user-friendly web interface.
- **OpenAI**: For accessing powerful AI models.
- **Pinecone**: For efficient vector indexing and similarity search.
- **Detectron2**: For advanced object detection tasks within images.
- **Sentence Transformers**: For generating textual embeddings.
- **Google API**: For integrating additional Google services.

Additional libraries and frameworks are listed in the `requirements.txt` file.

## Installation

To get started with TextSage, you'll need to install its dependencies.

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/TextSage.git
   cd TextSage
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
## Setup
Before running the application, ensure you have the necessary API keys and configurations set:

1. **API Keys**:

- Obtain API keys for OpenAI and Pinecone.
- Set these keys in your environment variables or a configuration file.

2. **Configuration File**:

- Create a config.json file in the root directory and fill it with your API keys and other necessary configurations.


## Running the Application

Running TextSage locally involves a few simple steps once you have completed the installation and setup. Here’s how you can get it up and running:

### Prerequisites

Before launching the application, make sure you have the following prerequisites installed and properly configured:

- **Python 3.9.6**: Ensure that Python is installed and working in your development environment.
- **API Keys**: Ensure that you have obtained the necessary API keys and added them to your environment variables or a designated configuration file as outlined in the [Setup](#setup) section.

### Steps to Run

1. **Open Terminal**
   - Open your terminal or command prompt.

2. **Navigate to the Project Directory**
   - Change into the directory where you have cloned the TextSage repository.
     ```bash
     cd path/to/TextSage
     ```

3. **Activate Python Environment** (Optional)
   - If you are using a virtual environment, activate it:
     ```bash
     source your_env/bin/activate  # On macOS and Linux
     .\your_env\Scripts\activate   # On Windows
     ```

4. **Start the Application**
   - Run the application using Streamlit:
     ```bash
     streamlit run app.py
     ```

### Accessing the Application

- **Web Interface**
  - After starting the application, Streamlit will provide you with a local URL in the terminal, typically:
    ```
    Local URL: http://localhost:8501
    Network URL: http://192.168.x.x:8501
    ```
  - Open a web browser of your choice and visit `http://localhost:8501` to interact with TextSage.


## Demonstrations

### Feature Demonstrations

#### Chat Feature Demo
![Watch the Chat Feature Demo](https://github.com/user-attachments/assets/499d457f-d2b1-4e51-9b5b-66910566097d)


#### Model Change Feature Demo[Model change.webm](https://github.com/user-attachments/assets/69078b4f-37b6-44a6-9b8b-966075232808)


![Watch the Model Change Demo](https://github.com/user-attachments/assets/f586adad-5af0-4896-ab71-d61610990073)



#### Clear Function Demo
![Watch the Clear Function Demo](https://github.com/user-attachments/assets/76337178-e164-4aad-b152-07b25f7af911)

  

## Troubleshooting

If you encounter any issues while starting the application, consider the following:

- **Dependencies**: Ensure all dependencies are installed correctly as mentioned in the [Installation](#installation) section.
- **API Keys**: Verify that all required API keys are correctly set in the environment or configuration files.
- **Port Availability**: Streamlit runs on port 8501 by default. Ensure that the port is available and not being used by another application.
- **Logs and Errors**: Pay attention to the console output. Errors or warnings there can provide additional information on what might be going wrong.

For more detailed errors and troubleshooting, refer to the official Streamlit documentation or the respective API service documentation used in TextSage.

Enjoy using TextSage to enhance your text processing and analysis projects!

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make to TextSage are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**
   - Navigate to the main page of the repository and click the "Fork" button in the top-right corner of the page to create a copy of the repository under your GitHub account.

2. **Create your Feature Branch**
   - After forking, clone the repository to your local machine and navigate into it:
     ```bash
     git clone https://github.com/yourusername/TextSage.git
     cd TextSage
     ```
   - Create a branch for your new feature:
     ```bash
     git checkout -b feature/AmazingFeature
     ```

3. **Commit your Changes**
   - Make your changes locally and commit them:
     ```bash
     git commit -m 'Add some AmazingFeature'
     ```
   - It's a good practice to frequently commit changes with descriptive messages, explaining what each commit achieves.

4. **Push to the Branch**
   - Push your changes to your GitHub repository:
     ```bash
     git push origin feature/AmazingFeature
     ```

5. **Open a Pull Request**
   - Go to the 'Pull requests' tab on the original repository and click on "New pull request".
   - Select your fork and branch to compare with the base branch of the original repository.
   - Review your changes and then submit the pull request with a comprehensive description of what your changes do.

### Additional Guidelines

- **Code Reviews**: All submissions require a review to ensure quality and functionality.
- **Coding Conventions**: Please adhere to the coding standards used throughout the project.
- **Testing**: If you are adding new functionality, please include tests that confirm its correctness.

By following these guidelines, you can contribute effectively and help improve TextSage. We look forward to seeing your innovative contributions!


   
   
