# Evaluation-Test-ArtExtract


### 📊 Model Performance Comparison

| Model Name                                                   | Test Loss | Accuracy (%) | Images per Class | Total Images | model architecture Link        |
|--------------------------------------------------------------|-----------|---------------|------------------|--------------|-------------|
| artist_model_resnet18_32                                     | 3.90837   | 30.87         | 32               | 736          | 🔗 [Link](https://github.com/SahilKadge/Evaluation-Test-ArtExtract/blob/main/task1/artist/artist_model_resnet18_200.py) |
| artist_model_resnet18_200                                    | 1.86816   | 57.22         | 200              | 4600         | 🔗 [Link](https://github.com/SahilKadge/Evaluation-Test-ArtExtract/blob/main/task1/artist/artist_model_resnet18_200.py) |
| artist_finetunned_resnet18_200                               | 0.71938   | 79.48         | 200              | 4600         | 🔗 [Link](https://github.com/SahilKadge/Evaluation-Test-ArtExtract/blob/main/task1/artist_style_genre_model.py) |
| artist_model_finetunned_resnet50_200                         | 0.75762   | 79.22         | 200              | 4600         | 🔗 [Link](https://github.com/SahilKadge/Evaluation-Test-ArtExtract/blob/main/task1/artist/artist_model.py) |
| artist_model_finetuned_with_ReduceLROnPlateau_resnet50_200   | 0.78254   | 78.35         | 200              | 4600         | 🔗 [Link](https://github.com/SahilKadge/Evaluation-Test-ArtExtract/blob/main/task1/artist/artist_model.py) |
| artist_resnet50_lstm_model                                   | 0.86103   | 74.78         | 200              | 4600         | 🔗 [Link](https://github.com/SahilKadge/Evaluation-Test-ArtExtract/blob/main/task1/artist/artist_model.py) |
