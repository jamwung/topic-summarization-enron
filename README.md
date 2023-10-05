# NLP on Enron Emails

![Title](header.png)

This project serves as a showcase of our expertise in natural language processing, with a focus on topic modeling and text summarization using state-of-the-art deep learning models from Hugging Face.

## Overview

In the digital age, managing and extracting valuable information from a deluge of emails presents significant challenges for individuals and organizations. In response to the challenges posed by overwhelming email volumes, our project aimed to enhance productivity and decision-making by efficiently processing and extracting insights from email data.

Leveraging natural language processing techniques, we successfully identified email topics and generated concise summaries, enabling users to streamline their email perusal process and alleviate information overload. By refining the dataset, applying topic modeling, and comparing summarization models, we demonstrated the effectiveness of these techniques in addressing email management challenges and providing practical solutions for individuals and organizations. Future work could focus on further refining the summarization models and exploring additional techniques to enhance accuracy and usability.

## Dataset

Our primary data source is the [Enron Email Dataset](https://www.kaggle.com/datasets/wcukierski/enron-email-dataset) from Kaggle. This comprehensive collection of emails and related documents from the Enron Corporation was obtained by the Federal Energy Regulatory Commission during its investigation of Enron's collapse and serves as the foundation for our analysis.

## Installation

To set up this project in your environment, you can use the provided `requirements.txt` file. Run the following command to install the necessary packages:

```bash
pip install -r requirements.txt
```

Moreover, as the raw dataset is more than 1GB in size, it is not included in the repository. Interested users may download it manually from the Kaggle website. Alternatively, it may be downloaded via Kaggle API as shown below. Further instructions on authentication can be found [here](https://www.kaggle.com/docs/api).

```
pip install kaggle
kaggle datasets download -d wcukierski/enron-email-dataset
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Thank you for joining us on our journey to enhance email management and decision-making through natural language processing. We look forward to sharing our insights and advancements in this exciting field.