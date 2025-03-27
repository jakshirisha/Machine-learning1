# ECG Anomaly Detection using Autoencoders

This project demonstrates the use of deep learning-based Autoencoders to perform anomaly detection on ECG signal data. An autoencoder is trained to reconstruct normal ECG signals, and samples with high reconstruction error are flagged as anomalies.

## Dataset
- **Name:** ECG5000 or ECG Anomaly Dataset
- **Source:** [Kaggle ECG Anomaly Detection](https://www.kaggle.com/code/devavratatripathy/ecg-anomaly-detection-using-autoencoders)
- **Features:** 140 continuous ECG signal points per sample
- **Labels:** 1 = Normal, 0 = Anomalous

## Project Structure

| File/Folder Name                          | Description |
|------------------------------------------|-------------|
| `ecg_autoencoder_anomaly_detection.ipynb` | Main notebook with code and analysis |
| `ecg 2.csv`                               | ECG dataset used for training and testing |
| `requirements.txt`                        | Python dependencies |
| `README.md`                               | Project overview and instructions |

## How It Works
1. Train an autoencoder only on normal ECG signals
2. Compute reconstruction error for test data
3. Use a threshold to detect anomalies
4. Evaluate performance using classification metrics and visualizations

## Instructions to Run
- Run in Jupyter or Google Colab
- Upload dataset `ecg 2.csv`
- Run all cells in the notebook

## License
This project is licensed under the MIT License.

