# A/B Testing Eniac’s Homepage: Boosting Conversions  
## Data Science Bootcamp Project – WBS Coding School  

### **Welcome to the A/B Testing Project!**  
This project focuses on improving Eniac’s website by testing variations of the “SHOP NOW” button to increase user engagement and iPhone 13 sales. Using data-driven decision-making, we aim to identify the best-performing button design.

---

## **Project Overview**  
Eniac’s website attracts significant traffic, but the current **Click-Through Rate (CTR)** of the "SHOP NOW" button is only 2%, creating a bottleneck in the conversion funnel. Through A/B testing, this project explores how design changes to the button impact user behavior and CTR.

---

## **Skills & Tools**  
- **Data Analysis**: Cleaning, organizing, and understanding experiment data.  
- **A/B Testing**: Designing experiments to compare multiple versions of a website element.  
- **Hypothesis Testing**: Using statistical methods to make data-driven decisions.  
- **Chi-Square Test**: Evaluating significance using Python’s `scipy` library.

---

## **The Challenge**  
Eniac seeks to optimize the CTR of its “SHOP NOW” button. The challenge is to determine which of the four button variations will best capture user attention and guide them further into the purchase funnel.  

---

## **User Journey**  

The steps for purchasing an iPhone 13 are as follows:  
1. Visit the homepage.  
2. Click the “SHOP NOW” button.  
3. Select an iPhone model.  
4. Add the product to the cart.  
5. Provide delivery and payment details.  
6. Confirm the purchase.  

---

## **Experiment Design**  

### **Test Variants**  
1. **Version A:** White "SHOP NOW" (current design).  
2. **Version B:** Red "SHOP NOW".  
3. **Version C:** White "SEE DEALS".  
4. **Version D:** Red "SEE DEALS".  

---

### **Key Metrics**  
1. **Click-Through Rate (CTR):** Percentage of users clicking the button.  
2. **Drop-Off Rate:** Percentage of users leaving the linked page without taking further action.  
3. **Homepage Return Rate:** Frequency of users returning to the homepage after clicking the button.

---

### **Hypotheses**  
- **Null Hypothesis (H₀):** All button variations have equal CTR, and any differences are due to chance.  
- **Alternative Hypothesis (H₁):** At least one button variation has a statistically significant difference in CTR.

---

### **Statistical Considerations**  
- **Significance Level (α):** 0.05 (95% confidence).  
- **Minimum Detectable Effect (MDE):** 20% improvement in CTR.  
- **Test Duration:** 14 days to cover two business cycles.

---

## **Analysis & Results**  

### **Statistical Testing**  
1. **Chi-Square Test:**  
   Evaluated if differences in CTR among the button versions were statistically significant.  

2. **Post-Hoc Analysis:**  
   Applied Bonferroni Adjustment for pairwise comparisons to identify the top-performing versions.

---

### **Key Findings**  
- **White buttons (Version A and Version C)** significantly outperformed red buttons (Version B and Version D).  
- **Version C (White “SEE DEALS”)** exhibited the highest CTR but was not significantly better than **Version A (White “SHOP NOW”)**.

---

## **Recommendations**  

### To further optimize results:  
1. **Focus on Top Performers:** Run a follow-up test comparing Version A and Version C.  
2. **Incorporate Secondary Metrics:** Consider drop-off rates and homepage return rates for a holistic evaluation.  
3. **Gather Qualitative Insights:** Use surveys or user feedback to refine designs further.

---

## **Conclusion**  
This project highlights the importance of data-driven experimentation in improving website performance. By leveraging A/B testing, Eniac can enhance user engagement, boost sales, and create a better user experience.  


