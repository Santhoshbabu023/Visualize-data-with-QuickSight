# Visualize-data-with-QuickSight
Amazon QuickSight is a cloud-based BI service for analyzing, visualizing, and sharing insights from data. In this project, I used QuickSight to analyze a Netflix dataset stored in S3, created visualizations, applied filters, and explored trends. The dashboard was then shared and exported as a PDF for easy access.

## Steps Followed

### 1. **Amazon QuickSight Setup**
   - Created an Amazon QuickSight account and utilized the free trial.
   - Used QuickSight’s integration with AWS services to access and analyze the dataset stored in Amazon S3.

### 2. **Dataset and S3**
   - **Dataset**: The project used the `netflix_titles.csv` file, which contains information about TV shows and movies on Netflix.
   - **S3 Bucket**: The dataset was uploaded to an Amazon S3 bucket. A `manifest.json` file was created and edited to point to the S3 URL of the dataset, ensuring QuickSight could access it properly.

### 3. **Creating Visualizations**
   - **Connecting QuickSight to S3**: Used the `manifest.json` file to connect QuickSight to the S3 bucket and ensure the dataset was processed correctly.
   - **First Visualization**: A visualization was created to analyze the **release year** of the Netflix titles. The `release_year` and `type` fields were used to break down the dataset.
   - **Using Filters**: Filters were applied to focus on specific data points like **Listed_in** and **Release Year**. Filters help refine the dataset, improve performance, and ensure data accuracy.

### 4. **Setting up a Dashboard**
   - Multiple visualizations were combined to create a dashboard.
   - The layout was adjusted to fit the graphs and renamed for clarity.
   - The dashboard was exported as a **PDF** for easy sharing.

### 5. **Key Insights**
   - The project provided insights into the **distribution of Netflix content by year** and **category** (Action & Adventure, TV Comedies, Thrillers, etc.).

## Key Tools and Technologies
   - **Amazon QuickSight**: For data visualization and analysis.
   - **Amazon S3**: To store the dataset.
   - **manifest.json**: To configure dataset access in QuickSight.

## Conclusion
Amazon QuickSight helped streamline the process of analyzing and visualizing the dataset, making it easier to gain insights and share the results in an interactive, actionable format.
