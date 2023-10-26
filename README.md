
# AIL303m - Mini Capstone

## Team Details
- **Team**: Nhóm 1
- **Members**:
    - Đinh Ngọc Ân
    - Trần Hoàng Minh
    - Nguyễn Hoàng Việt
    - Phạm Ngọc Hải Nam
    - Nguyễn Hoàng Anh
    - Vũ Minh Thông


## Workflow

1. **Collect data**: Collecting data on Kaggle
2. **Preprocessing**: Apply preprocessing technique to enhance data
3. **EDA**: Apply EDA technique to know more about our data
4. **Building our model**: Implement ML models
5. **Visualization**: Visualize our results
6. **Fine-tuning**: Fine-tuning model's hyperparameters to achieve much more higher performance

## Project Setup
The project starts by importing a variety of modules necessary for data processing, visualization, and machine learning. These modules include:
- Data handling and processing: `pandas`, `numpy`
- Visualization: `plotly`, `matplotlib`, `seaborn`, `folium`
- Machine Learning: `sklearn`, `xgboost`

1. **Enviroment Setup**:
   - Set up a virtual environment (optional but recommended).
    - Activate the virtual environment:
      ```bash
      source venv/bin/activate  # On macOS and Linux
      ```
      OR
      ```bash
      .\venv\Scripts\activate  # On Windows
      ```
    - Install the necessary packages:
      ```bash
      pip install -r requirements.txt
      ```

2. **Data Preparation**:
    - Place your image data inside the `data/images/` directory.
    - Update paths in `main.py` accordingly if you have different directory structures or names.

3. **Run the HTR System**:
    - Navigate to the `src/` directory:
      ```bash
      cd src/
      ```
    - Run the `main.py` script:
      ```bash
      python main.py
      ```

## Data Acquisition
The team has sourced their train and test datasets from Google Drive. 
- The train dataset has 2000 samples and 21 features.
- The test dataset has 1000 samples and 21 features.

---

For more details, please refer to the original Jupyter notebook.
