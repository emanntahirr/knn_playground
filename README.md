# knn_playground
I made this project to really **understand how K-Nearest-Neighbours** works. I wanted to see what its doing.

I coded it from scratch in Python, potted the decision boundaries, and played around with different **K values** and **noise levels** to see how the model reacts.

---

## What I Learned

- How KNN makes predictions using distances and majority voting  
- How changing **K** affects overfitting vs. generalisation  
- Why models can be sensitive to noise and small data changes  
- How to visualise decision boundaries in 2D datasets  

---

## Tools & Libraries
- Python  
- NumPy  
- Matplotlib  
- scikit-learn  
- Jupyter Notebook  

---

## Results
I generated a simple 2D dataset (two moons) and plotted how KNN separates the classes.  
You can clearly see how the decision boundaries shift when you adjust **K** or add noise.

| K | Accuracy (approx.) |
|---|--------------------|
| 1 | 0.86 |
| 3 | 0.90 |
| 5 | 0.92 |
| 7 | 0.89 |

---

## How to Run
```bash
pip install notebook numpy matplotlib scikit-learn
jupyter notebook knn_playground.ipynb
