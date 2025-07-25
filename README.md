<h2 align="center"> Namaste!🙏🏻 </h2>

<h3 align="center"> Boring .csv files? Not anymore! Built a full-fledged visual dashboard powered by AWS 🚀 </h3>

---
<h3> Project Overview </h3> 

Services Used:
- 🪣 Amazon S3 (for storing CSV files)  
- 📈 Amazon QuickSight (for visualizing the data)

</br>

### 🔍 What I Learned:
- Storing and organizing datasets using **Amazon S3**
- Creating a **manifest file** to connect S3 with QuickSight
- Designing visuals with filters, KPIs, and charts
- Understanding data storytelling and dashboarding basics

</br>

## 📋 Checklist: What to Do & Remember

Step 1: Prepare the Dataset
- Try to use excel or google sheets
- Name the file as `sample-filename.csv`
  ![Dataset](Netflix-data.png)
</br>

Step 2: Upload dataset to S3 bucket
- Create a s3 bucket
- Upload the dataset
- Enable versioning (for future use)
  </br></br>

*Multiple datasets can be used from different s3 buckets and manifest files.* 
</br></br>

Step 3: Create a manifest file for quicksight 
- Like this

  ![Manifest-code](manifest.png) 
</br>

Step 4: Create QuickSight Dashboard
- Create quicksight account carefully (untick all unneccessary option to avoid extra costing)
- Go the datasets, then new datasets.
- Select S3, Provide 'data source' and 'manifest file' (Upload or through S3 url)
- Visualize
</br>
  
  ![Quicksight](Quicksight-dataset-creation.png)
</br>

**And Tadaaa.. QUICKSIGHT is all ready!** 
</br>

Step 4: Build Visuals
- Select all the parameters 
- Charts: Sales by Region, Category-wise Performance, Time Series Trend
- Filters: Region, Product, Date Range
- KPIs: Total Sales, Highest Category
- Add drill-downs and interactivity to stand out!
</br>
  
  ![Quicksight-charts](Quicksight-charts.png)

</br>

*Can Import data later-on add calculated fields too for further computations*

</br>
