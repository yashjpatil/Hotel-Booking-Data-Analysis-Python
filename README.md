# 🏨 Hotel Booking Data Analysis Project
Hotel booking data analysis using Python

This project explores and analyzes hotel booking data to uncover patterns in guest behavior, booking trends, and cancellations. It focuses on comparing two types of hotels — **City Hotel** and **Resort Hotel** — based on several key metrics.

---

## 📊 Objective

To analyze hotel booking data and answer business questions like:
- Which hotel type receives more bookings?
- What percentage of bookings are canceled?
- Are cancellations more frequent in a particular hotel type?
- How far in advance do guests usually book?
- Which months or customer types lead to more cancellations?

---

## 📁 Dataset

- **Source**: [Kaggle – Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Rows**: 119390
- **Columns**:  36
- **Features Include**:
  - Booking dates, hotel type
  - Is the booking canceled?
  - Lead time
  - Number of adults/children
  - Country, market segment, deposit type, etc.

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🔍 Key Data Cleaning Steps

- Removed duplicate entries
- Handled missing values in important columns like `country`, `agent`, and `children`
- Dropped unnecessary columns like `company`

---

## 📈 Key Visualizations & Insights

- **Bookings per Hotel Type**:
  - City Hotel has more bookings than Resort Hotel

- **Canceled vs Not Canceled**:
  - Cancellations are higher in City Hotel

- **Average Lead Time**:
  - Guests book City Hotel farther in advance compared to Resort Hotel

---

## 💡 Conclusion

- Guests prefer City Hotels but also cancel more often
- Long lead times may lead to more cancellations
- Business strategy should focus on optimizing for high cancellation segments

---

## 📌 How to Run

1. Clone the repo
2. Place `hotel_booking.csv` in the same directory
3. Open `hotelbookingdataanalyst.ipynb` in Jupyter Notebook
4. Run all cells for full analysis and charts

---

## 📚 Future Improvements

- Add machine learning to predict cancellations
- Integrate interactive dashboards using Streamlit or Power BI
- Deeper customer segmentation analysis

---

## 🙋‍♂️ Author

Yash Patil – Aspiring Data Analyst
