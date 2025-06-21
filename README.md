# Projects & Demos by Ha Pham


## Machine Learning

- [Thesis project: Swedish Historical Handwritten Text Recognition with Visual Language Model](https://github.com/hoanghapham/visual-language-models-htr)

    In this project, I investigate if a visual language model (Florence-2) can perform Handwritten Text Recognition on Swedish historical manuscripts. Results show that a pipeline made up of Florence-2 models can outperform a classical HTR pipeline (using YOLO for text detection and segmentation, then TrOCR for text recognition). However, the Florence pipeline is much more computationally demanding.

    **Main tools:** scikit-learn, PyTorch, Transformer, Hugging Face, Gradio, YOLO, TrOCR, Florence

    [Hugging Face Demo](https://huggingface.co/spaces/nazounoryuu/vlm-htr)

- [Ideology and Power Identification in Parliamentary Debates](https://github.com/hoanghapham/power-identification?tab=readme-ov-file)

    This is a binary classification task in which my group and I determine if a statement in parliamentary debates belongs to the coalition or opposition of the government side. 

    **Main tools:** scikit-learn, PyTorch, Transformers

- [Model samples](https://github.com/hoanghapham/model_samples)

  A collection of sample codes for machine learning models, from models coded from scratch using `numpy` (Stochastic Gradient Descent, K-means, Linear & Logistics Regression, Neural Networks), to models leveraging PyTorch modules.
    **Main tools**: scikit-learn, numpy, PyTorch


## Software Engineering

- [Simple Search](https://github.com/hoanghapham/simple-search)

    A simple tool to search through text files and rank results using TF-IDF, meant for demonstration purpose.

    **Main tools:** Python, reverse index


## Data Engineering
- [Music ETL](https://github.com/hoanghapham/music-etl)

    In this project, I combine the real Million Song Dataset with data coming from Spotify API. With this pipeline, new researchers familiar with the old Million Song Dataset can get new information about the songs from Spotify, such as new audio features, song popularity, artist popularity...

    **Main tools:** Amazone S3, Redshift, Amazon EC2, Prefect, Terraform

- [Github Archive Event Pipeline](https://github.com/hoanghapham/github-archive-pipeline/tree/master)

    With this project, I pull in data from GH Archive, transform and analyze them to get some information about the activity of public GitHub repositories over time.

    **Main tools:** Terraform, Google Cloud Storage, BigQuery, Airflow, dbt, Google Data Studio


- [dbt CI demo](https://github.com/hoanghapham/dbt_ci_demo/tree/demo)

    A small demo on how to use dbt with GitHub Action to enable CI test.

    **Main tools:** dbt, GitHub Action


## Data Analytics

- [Vietnam War Bombing Operations](https://github.com/hoanghapham/vietnam_war_bombing)

    In this project, I analyzed the Vietnam War's bombing patterns using data from the THOR database, and wrote two articles exploring this topic from both analytical and historical perspectives.

    **Main tools:** R, R Markdown, ggplot2, plotly
