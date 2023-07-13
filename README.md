# ChartSumm: A Comprehensive Benchmark for Automatic Chart Summarization of Long and Short Summaries

Authors: Raian Rahman, Rizvi Hasan, Abdullah Al Farhad, Md Tahmid Rahman Laskar, Md. Hamjajul Ashmafee, Abu Raihan Mostofa Kamal
Accepted in: [The 36th Canadian Conference on Artificial Intelligence (CANAI)](https://www.caiac.ca/en/conferences/canadianai-2023/home)
Paper link: [Link]()

### Updates

* Add Abstract
* Add data

## Abstract
Automatic chart to text summarization is an effective tool for the visually impaired people along with providing precise insights of tabular data in natural language to the user. A large and well-structured dataset is always a key part for data driven models. In this paper, we propose ChartSumm: a large-scale benchmark dataset consisting of a total of 84,363 charts along with their metadata and descriptions covering a wide range of topics and chart types to generate short and long summaries. Extensive experiments with strong baseline models show that even though these models generate fluent and informative summaries by achieving decent scores in various automatic evaluation metrics, they often face issues like suffering from hallucination, missing out important data points, in addition to incorrect explanation of complex trends in the charts. We also investigated the potential of expanding ChartSumm to other languages using automated translation tools. These make our dataset a challenging benchmark for future research.


## Data
Link to data: [Drive Link](https://drive.google.com/drive/folders/1HPsFUojoHctFD2AGuotRPKRz-o0jXfRJ?usp=sharing)

### Data Description
The dataset is provided in JSON format, with each file containing the following fields:

- x_label: The label for the x-axis of the data.
- y_label: A list of lists containing the labels for the y-axis.
- data: A dictionary where each key has a list of values for that specific column on data
- title: The title or description of the dataset.
- summary: A summary of the dataset providing key information and statistics related to the voting intention.
