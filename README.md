# GSML-Analysis Project

---

## **Purpose**

Class project to learn ML and apply ML to a global warming vs sea level rise model. Current models lack resilience to missing parameters. The cutoff year of 2021 represents a unique opportunity to evaluate the impact of what drastic measures to improve sustainability may have implemented on a global scale resulting from the global decrease in activity as a result of COVID restrictions.

---

## **Data Set**

This data set was assembled through by incorporating a multitude of Kagel datasets to align the period of interest, 1880-2021. There is also a subset of data which required being hand built using available records online, one example is the merchant shipping data tracking the number of active merchant vessels.

---

## **Running the Project**

1. First run `pip install statsmodels` to get the necessary tool set.
2. To run the project simply run each cell in `prepareData1.ipynb`, then `prepareData2.ipynb` to generate the correct, normalized, prepared dataset file in the **Outputs** folder.
3. Then run the `Test_Models.ipynb` file located in the **Model_Outputs** folder to generate the predictions in the same folder.
4. Finally, to recreate the graphs run `graph_data.ipynb` and then `graph_data2.ipynb` to generate the plots in the **Generated_Plots** folder.

---

## **FUTURE TODOs:**

- Find more data!
- Determine what input values will slow the sea level rise and taper the temperature rise (aka what do we need to achieve in what areas to get a stable planet)
