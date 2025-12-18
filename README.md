# Data-Modelling-Competition-BirdCLEF
This project focuses on developing a machine learning–based data modeling approach to automatically identify animal species from acoustic recordings using passive acoustic monitoring data from the BirdCLEF 2025 competition.

Ecological restoration requires accurate and scalable biodiversity monitoring to evaluate conservation outcomes. Traditional field surveys are often costly and difficult to conduct at scale. This project leverages the BirdCLEF 2025 dataset to apply passive acoustic monitoring (PAM) and machine learning techniques for automated species identification.

The dataset contains acoustic recordings from birds, amphibians, mammals, and insects collected in the El Silencio Natural Reserve, Magdalena Valley, Colombia—one of the most biodiverse regions in the world and currently threatened by deforestation and land-use change. Due to limited labeled data, this project explores efficient data modeling strategies that can also utilize unlabeled soundscape recordings.

The goal of this project is to build an automated species classification model that supports continuous biodiversity monitoring, assists ecologists in assessing habitat restoration, and strengthens conservation efforts in vulnerable tropical ecosystems.

Dataset Structure:
train_audio/ = Short labeled audio recordings of individual species
train_soundscapes/ = Labeled environmental soundscapes
train.csv = Training labels and metadata
taxonomy.csv = Taxonomic information for each species
recording_location.txt = Recording location details
sample_submission.csv = Submission format example
