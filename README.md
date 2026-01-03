# Sai Kiran Reddy Kondreddygari - Portfolio

🌐 **Live**: https://sai18kiran.github.io (Deploy instructions below)

## About
Financial Analyst portfolio showcasing 4+ years of experience in financial modeling, investment analysis, portfolio management, and strategic financial planning across diverse industry sectors.
## Features
- 📊 **5 Real Data Engineering Projects** with GitHub repository links
- 🔗 **Verifiable Work** - Direct links to source code for technical review
- 📱 **Fully Responsive Design** - Mobile-first approach with modern UI
- 📄 **Downloadable Resume** - Latest PDF with contact information
- 🎯 **JSON-Driven Content** - Easy updates without touching HTML/CSS
- ⚡ **GitHub Pages Ready** - Static site optimized for free hosting

## Projects Showcased

### 1. Real-Time IoT Temperature Analytics (Spark & Kafka)
**GitHub**: https://github.com/Sai18Kiran/spark-and-kafka_iot-data-processing-and-analytics
- Real-time temperature analysis from U.S. nationwide IoT sensors
- **Tech**: Apache Spark, Kafka, PySpark, Python, AWS
- **Metrics**: 10,000 data points, 2,086 sensors, 4 key analytics

### 2. Data Pipeline with DBT on GCP
**GitHub**: https://github.com/Sai18Kiran/data-pipeline-with-dbt-using-airflow-on-gcp
- Modern data engineering pipeline with Astronomer, DBT, Soda, Metabase
- **Tech**: Apache Airflow, DBT, Google BigQuery, Docker, GCP
- **Metrics**: 5 technologies, Star schema, Containerized deployment

### 3. Machine Learning Fraud Detection on AWS
**GitHub**: https://github.com/Sai18Kiran/fraud-detection-using-machine-learning
- ML-based fraud detection using XGBoost and RandomCutForest
- **Tech**: AWS SageMaker, Lambda, API Gateway, Kinesis, Python
- **Metrics**: 284,807 transactions, 2 ML algorithms, Real-time API

### 4. Banking Analytics with PowerBI
**GitHub**: https://github.com/Sai18Kiran/financial-insights-in-banking-data-using-powerbi
- Comprehensive banking analytics and visualization platform
- **Tech**: Power BI, DAX, Excel, Data Modeling, Financial Analytics
- **Metrics**: 2 datasets, Multi-dimensional analysis, Interactive dashboard

### 5. Real-Time Fraud Detection with Apache Flink
**GitHub**: https://github.com/Sai18Kiran/lab-fraud-detection
- Interactive fraud detection system using streaming technologies
- **Tech**: Apache Flink, Kafka, Docker, Java, TypeScript, Web Interface
- **Metrics**: Real-time processing, Web UI at localhost:5656, Containerized

## Technical Architecture

### Frontend
- **Languages**: HTML5, CSS3, JavaScript
- **Design**: Responsive, Mobile-First (6 breakpoints)
- **Styling**: Modern UI with smooth animations and gradients
- **Framework**: Vanilla JS with jQuery for interactions

### Backend
- **Content Management**: JSON-driven architecture (`data/profile.json`)
- **Dynamic Loading**: JavaScript profile loader for content injection
- **Static Generation**: No build tools required, direct file serving
- **Hosting**: GitHub Pages compatible with `.nojekyll` configuration

### Data Structure
```
├── index.html              # Main template with placeholders
├── data/
│   └── profile.json       # Complete profile data (projects, skills, etc.)
├── assets/
│   ├── css/              # Compiled stylesheets
│   ├── js/               # Profile loader + UI interactions
│   ├── sass/             # Source stylesheets (SCSS)
│   ├── sai-profile.jpg   # Professional headshot
│   ├── Sai_Kiran_Resume.pdf  # Latest resume
│   └── webfonts/         # Font Awesome icons
├── images/
│   ├── org/              # Company logos (UnitedHealth, etc.)
│   ├── edu/              # University logos (Webster, Bharti)
│   └── project/          # Project screenshots and media
└── scripts/              # Deployment automation
```

## Skills Highlighted

### Programming & Scripting
Python, SQL, Bash, Scala, JavaScript, TypeScript

### Data Engineering & Pipelines
ETL/ELT Pipelines, Data Modeling, Apache Airflow, dbt, Apache Spark, Apache Beam

### Cloud & Distributed Systems
AWS (S3, Lambda, Glue, EMR, Redshift, Athena), GCP (BigQuery, Dataflow), Azure Data Factory

### Streaming & Real-Time Processing
Apache Kafka, AWS Kinesis, Spark Streaming, Apache Flink, Apache NiFi, Apache Hive

### AI & ML Tooling
MLflow, TensorFlow, Feature Stores, Jupyter, Hugging Face Transformers, OpenAI APIs, LLMs

## Deployment Instructions

### Prerequisites
1. GitHub account (Sai18Kiran)
2. Git installed locally
3. Repository ready for deployment

### Step 1: Create GitHub Repository
1. Go to https://github.com/Sai18Kiran
2. Click "New Repository"
3. **Repository name**: `Sai18Kiran.github.io` (EXACTLY this name for personal pages)
4. Set to **Public**
5. **DO NOT** initialize with README (we already have content)
6. Click "Create repository"

### Step 2: Push Portfolio to GitHub
```bash
# Navigate to portfolio directory
cd "C:\Users\Lenovo\portfolios\sai"

# Verify git status (should show clean working tree)
git status

# Push to GitHub (repository must exist first)
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to repository: https://github.com/Sai18Kiran/Sai18Kiran.github.io
2. Click **Settings** tab
3. Scroll to **Pages** section (left sidebar)
4. Under **Source**, select "Deploy from a branch"
5. Select **Branch**: `main`
6. Select **Folder**: `/ (root)`
7. Click **Save**

### Step 4: Verify Deployment
1. Wait 2-5 minutes for GitHub Pages to build
2. Visit: https://sai18kiran.github.io
3. Verify all features work:
   - ✅ Navigation links
   - ✅ Project GitHub links
   - ✅ Resume download
   - ✅ Contact information
   - ✅ Mobile responsiveness

## Customization Guide

### Update Profile Information
Edit `data/profile.json` to modify:
- Personal details and contact info
- Work experience and achievements
- Skills and certifications
- Project descriptions and links
- Education background

### Add New Projects
```json
{
  "id": "new-project-id",
  "title": "Project Title",
  "year": "2024",
  "shortDescription": "Brief description for cards",
  "detailedDescription": "Detailed description with achievements",
  "techStack": ["Technology", "Stack", "Used"],
  "links": {
    "github": "https://github.com/Sai18Kiran/repo-name"
  },
  "metrics": [
    { "label": "Metric Name", "value": "Value" }
  ]
}
```

### Update Styling
- Modify `assets/sass/` files for design changes
- Recompile CSS: `sass assets/sass/main.scss assets/css/main.css`
- Colors configured in `data/profile.json` under `siteConfig.themeColors`

## Maintenance

### Regular Updates
- **Monthly**: Add new projects and update achievements
- **Quarterly**: Update skills and certifications
- **Annually**: Refresh design and add new features

### Performance Optimization
- Optimize images in `images/` directory
- Minimize JSON file size
- Monitor Core Web Vitals via Google PageSpeed Insights

## Contact Information
- **Email**: kondreddygarisaikiranreddy18@gmail.com
- **LinkedIn**: https://linkedin.com/in/sai-kiran-reddy-kondreddygari
- **Phone**: +1 (917) 704-9894
- **Location**: Saint Louis, MO

## License
This portfolio template is based on Editorial by HTML5 UP (html5up.net) and is free for personal and commercial use under the CCA 3.0 license.

---

🚀 **Ready for deployment!** Follow the deployment instructions above to launch at https://sai18kiran.github.io
