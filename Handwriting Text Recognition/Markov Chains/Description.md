### Sherlock Holmes Story Generator
---

**Overview:**  
This project aims to generate Sherlock Holmes stories using Markov Chains. Markov Chains are mathematical systems that model transitions from one state to another, based on certain probabilities. In this case, the states represent words, and the transition probabilities represent the likelihood of one word following another in the text.

**Methodology:**  
To create the Markov Chain model, we first tokenize the text into words and then build a dictionary to store transition probabilities between words. We count how often each word follows another in the text and calculate the probability of transitioning from one word to another.

**Generating Stories:**  
Once the Markov model is constructed, we simulate a random walk through the model, starting from a chosen word. At each step, we select the next word based on the transition probabilities from the current word. By repeating this process, we generate a sequence of words that form a new Sherlock Holmes story.

#### Useful Links:
- [Navigate to the Dataset](./Dataset)
- [Images for the Word Cloud](./Sherlock%20Holmes%20Silhouette)
- [View My Jupyter Notebook File](./Sherlock%20Holmes%20Stories.ipynb)
