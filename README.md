
# mock-localstack-s3

## Description
mock-localstack-s3 is a versatile tool designed to simulate AWS S3 buckets locally. This project facilitates the development and testing of cloud-based applications by integrating seamlessly with LocalStack, providing a reliable and efficient environment for handling S3 operations without the need for actual AWS resources.

## Features
- **Local Simulation of S3 Buckets:** Mimic AWS S3 operations locally to speed up development and testing.
- **Integration with LocalStack:** Fully compatible with LocalStack to ensure a smooth workflow.
- **Ease of Use:** Simple setup and operation, enabling developers to focus on their application logic rather than infrastructure management.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
- Docker
- Python 3.x
- Any additional dependencies listed in `requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/guibdutra/mock-localstack-s3.git
   ```
2. Navigate to the cloned directory:
   ```bash
   cd mock-localstack-s3
   ```
3. Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
To start simulating S3 buckets locally, follow these steps:
1. Start LocalStack using Docker:
   ```bash
   docker-compose up -d
   ```
2. Execute the main script to begin the simulation:
   ```bash
   python main.py
   ```

## Contributing
We welcome contributions! Please feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries or further information, you can reach out to Guilherme Dutra at guibdutra@icloud.com .

## Acknowledgments
- Thanks to all contributors who have helped to improve this tool.
- Special thanks to the LocalStack community for their continuous support and collaboration.
