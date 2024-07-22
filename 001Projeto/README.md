# Project 001: Opinion Survey Data Analysis 📊

## Challenge
Analyze simulated data from a polling company to gain insights into the profile of participants and their responses. 🔎

## Tools
Python (Pandas) 🐍, KNIME (No-Code) 🤖

## Methodology
CRISP-DM 🔁

## Highlights
* **Data Joining:** Consolidation of five sets of data into a single table with complete information. 📊
* **Demographic Analysis:** Age, gender, region and income of participants.
* **Behavior Analysis:** Use of Pix for different purposes.
* **Insights Generated:** Identification of patterns and trends for strategic decisions. 📈

## Learnings
* **Data Manipulation with Pandas:** `merge`, `astype`, `pd.to_datetime`. 🐍
* **Data Transformation:** Conversion of responses into lines.
* **Time and Project Management:** Deadlines and communication.
* **Exploration of New Tools:** KNIME.


## Observation
The project demonstrates skills in data manipulation, exploratory analysis, descriptive statistics and generation of insights. 💪

---

# Case received:

In the corporate world, data is essential to support strategic decisions. Opinion polls emerge as valuable sources of this data. To conduct them effectively, it is essential to have individuals willing to share their perspectives.

Companies called "Panels" play a crucial role in this context. They establish a bridge (preserving anonymity) between their community of participants, known as Panelists, and large corporations looking for insights.

This exercise focuses on simulated data from a Panel company. The organization maintains a group of Panelists (file `Painelista.csv`) who are motivated to participate in opinion polls in exchange for financial compensation.

Panelist responses are collected through Surveys (`Pesquisa.csv` file), with two surveys already registered for this exercise.
The relationship between Panelists and Surveys is documented in the `Panelista_Pesquisa.csv` file. Each Panelist's contributions to each survey are stored in `Response.csv`.
The surveys are composed of Questions, and the alternative answers are listed in `OpcoesDeRespostas.csv`.
A diagram illustrating the interconnections between these files can be found below for a visual understanding of the process.

<p align="center">
  <img src="https://github.com/raulfbr/portifolio/blob/main/001Projeto/data/DiagramaRelacional.png?raw=true" alt="DiagramRelacional" width="50%">
</p>


### 1. Joining Data Sets
Merge the five sets of data and create a single table that includes all responses from the 600 Panelists in both surveys. This table must contain 5551 rows (one for each answer) and 14 columns. An example with 23 lines of this table can be found in the file `Modelo01.csv`.

### 2. Data Analysis
Use the data in your preferred format to answer the following questions:

 **a.** What is the mean and standard deviation of the age of the 600 Panelists? It may be necessary to make some approximations to answer this question, and your approximation methodology will be evaluated.

 **b.** What percentage of Panelists have child(ren) and are female?

 **c.** What is the percentage of Panelists in the SOUTH region who have a monthly income of up to R$2,999?

 **d.** What percentage of the 600 Panelists use Pix for each of the purposes researched?

 **e.** What percentage of Panelists use Pix to [Transfer money to friends and family] OR [Pay for purchases in online stores] and are male?

More than the final answers, the focus is on implementing your solutions in Python. Therefore, it is crucial to send the ipynb file with the developed code to get the answers.

Any open-source tool can be used, but the preference is:
- Only use Pandas for Python solutions

## How to Contribute

To contribute:
1. Set up your development environment.
2. Clone the repository and run locally.
3. Create a branch, deploy and make a pull request with a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).
