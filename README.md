# VieMedKG: Knowledge Graph and Benchmark for Traditional Vietnamese Medicine

### 1. Contributors:

- Tam Trinh
- Anh Hoang
- Hy Truong Son (Correspondent / PI)

### 2. Setup

To set up the project, follow these steps:

#### 1. Clone the project

```bash
git clone https://github.com/HySonLab/VieMedKG.git
```

#### 2. Create a Conda Environment

First, create a new conda environment named `vietmedkg`:

```bash
conda create --name vietmedkg python=3.8
```

Activate the newly created environment:

```bash
conda activate vietmedkg
```

#### 3. Install Required Packages

Once the environment is activated, install the required packages using `pip` and the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

#### 3. Usage

Please navigate to the file `key.env` and fill in the information:

```
OPENAI_API_KEY = ""
GOOGLE_API_KEY = ""
URI=""
USER="neo4j"
PASSWORD=""
```

#### 4. Project Structure

```
.
├── data/                 # Data files
├── experiments/          # Experiments code
├── preprocessing/        # Data creation code
├── results/              # Output result of the experiments
├── key.env               # The API key to run the code
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
```

### 5. Contribution Guidelines

We welcome contributions from the community. If you're interested in contributing to the VieMedKG project, please follow these guidelines:

- **Fork the repository**: Start by forking the repository to your GitHub account.
- **Create a branch**: Create a new branch for your feature or bug fix.
- **Commit changes**: Make your changes and commit them with clear and descriptive messages.
- **Submit a pull request**: Once you're satisfied with your changes, submit a pull request to the main repository for review.

### 6. License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
