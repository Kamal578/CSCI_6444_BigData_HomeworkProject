# CS6444 Big Data and Analytics  
## Class Project #1  
### R and Graph Analytics  

**Due Date:** 15 March 2026  

Prior to completing this assignment, create or use your existing **Kaggle account**. Select **R** as the programming language of the notebook.  

To ensure that your code is reproducible, you are expected to submit through **Blackboard** the reference to the **Kaggle notebook**.

Requirements:

- All datasets must be included on your Kaggle account.
- Ensure the code is fully runnable through the shared reference (test without logging in).
- Provide **clear and informative comments** for each step of your solution.

This is a **team assignment**, and you are expected to work effectively as a team by distributing sub-tasks between the two members.

---

# 1. Data Set

You are responsible for choosing a dataset that represents **objects and relationships between them**, allowing it to be formalized under **Graph Theory** and analyzed using **Graph Analytics**.

### Some open data repositories to consider (not limited to):

- Kaggle Datasets  
- Open Data NYC  
- UCI Machine Learning Repository  
- OpenML Datasets  
- Computer Society – IEEE DataPort  
- Google Research Datasets  
- Hugging Face Datasets  
- The World Bank Datasets  

Each team must work with a **unique dataset**, and it is the team’s responsibility to ensure uniqueness.

To avoid cases where different teams use the same dataset, **post your dataset and description on the class Discussions on Blackboard**.

### Dataset Requirements

- Must include **at least 50,000 objects (vertices)**.
- It is **recommended (not required)** to consider assigning **weights to edges**.

You must describe:

- The **initial dataset**
- The **business or social problem** the data represents
- Why you selected the dataset

Provide **metrics and properties** of the resulting initial graph, including:

- Number of nodes
- Number of edges
- Sparsity
- Directedness (arrowness)
- Node properties
- Edge properties
- Edge weights (if applicable)

---

# 2. Install igraph

Install the **igraph package** from one of the **CRAN mirrors**.

---

# 3. Graph Analytics Experimentation

Experiment with graph analytics using the **Tutorial on Graph Analytics** document available on:

**Blackboard → Outline → Tutorials section**

Try to **implement the whole tutorial on your own computer** before starting the assignment.

Your dataset is large, so initially you may see just a **large blue blob** in visualization. You may need to **simplify the graph** to execute the project.

If simplification is required, **describe your approach**.

You may use the `simplify()` function, but **additional techniques are required**.

Possible simplification ideas:

- Degree filtering
- Using subject keywords
- Assigning random weights
- Other filtering techniques

This will be an **important part of the evaluation**, reflecting how efficient your simplification technique is.

---

# 4. Explore Additional igraph Functions

Explore **at least 10 igraph functions** and apply them to your graph.

Requirements:

- Do **NOT** select functions already used in the **Graph Analytics tutorial** (check [used_in_tutorial.md](used_in_tutorial.md)).
- Some **R programming** may be required.
- Several books are available on **Blackboard** for reference.

---

# 5. Graph Analysis Tasks

Determine the following:

- **(a)** Central node(s) in the graph  
- **(b)** Longest path(s)  
- **(c)** Largest clique(s)  
- **(d)** Ego network(s)  
- **(e)** Power centrality  
- **(f)** Communities  

For details, refer to:

- Lecture slides
- Shared materials (books and tutorials)

---

# 6. Graph Visualization

Graphs with too many vertices and edges will look messy in plots.

Filter vertices and edges to produce a visualization containing **30–100 vertices**.

Differentiate graph components visually:

### Vertices
- Color
- Size
- Shape

### Edges
- Color
- Type

Consider assigning **weights to edges** and visually differentiating them accordingly.

---

# 7. Deliverables

Submit the **reference to your Kaggle (R) Notebook** through **Blackboard**.

Your deliverable should include:

- A listing of **all R functions used in the assignment**
- Description and demonstrations of the **igraph functions explored in item #4**

Also include:

- Answers for **item #5**
- Solutions for **item #6**
- **Images of graph visualizations** inside the notebook

For each image:

- Use an **appropriate figure number**
- Include a **caption**
- Provide **references in the text**

Clearly explain:

- What each function does
- Any problems encountered
- How you solved them

---

# 8. Project Value

**Total: 15 points**

| Component | Points |
|---|---|
| Approach (loading data, simplifying, etc.) | 3 |
| Item #4 demonstrations | 3 |
| Item #5 demonstrations | 5 |
| Item #6 demonstrations | 3 |
| Write-up on insights from the data | 1 |

---

# Important Notes

- Ensure your **code is fully runnable by a guest user** (ask peers to verify).
- Show **all work from items 1 through 8**.
- Provide **sufficient comments and descriptions**.

Your report must clearly demonstrate **your understanding of the subject**.

The **most important element affecting evaluation is your comments**.

Results without interpretation are not meaningful.

Do not only present function outputs — **explain what they mean and compare results where appropriate**.

Both the **team and the dataset must be unique across all teams**.