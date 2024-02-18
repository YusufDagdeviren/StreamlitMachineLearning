[TR]

# Streamlit ve Scikit-learn ile Etkileşimli Web Uygulaması

Farklı veri kümelerini ve sınıflandırıcıları keşfedin. Streamlit, makine öğrenimi projeleriniz için basit web
uygulamaları oluşturmanıza olanak tanır.  
Daha fazla bilgi için resmi [streamlit web sitesine](https://www.streamlit.io/) bakın.

## Yükleme İşlemi

İhtiyacınız olan bağımlılıklar:

````console
pip install streamlit
pip install scikit-learn
pip install matplotlib
````

Veya:

`````console
pip install -r requirements.txt
`````

## Lokalde Kullanım:

````console
streamlit run main.py
````

## Docker İle Kullanım:

````console
# Docker image'ını lokalde build edin
docker build -t <image_name> .
# Docker container'ı ayağa kaldırın
docker container run -p 8501:8501 <image_name>
````

[EN]

# Interactive Web App with Streamlit and Scikit-learn

Explore different datasets and classifier. Streamlit lets you create apps for your machine learning projects with simple
Python scripts.  
See official [streamlit website](https://www.streamlit.io/) for more info.

## Installation

You need these dependencies:

```console
pip install streamlit
pip install scikit-learn
pip install matplotlib
```

Or

`````console
pip install -r requirements.txt
`````

## Usage - Local

```console
streamlit run main.py
```

## Usage - Docker

```console
# Build a local docker image
docker build -t <image_name>
# Run the image
docker container run -p 8501:8501 <image_name>
```
