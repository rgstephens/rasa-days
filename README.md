# Rasa Days

This repo holds the Rasa Days lab content.

## Rasa Days Presentation Materials

Links to existing presentation materials:

- [Rasa Day @ Telekom](https://docs.google.com/presentation/d/10ybPJSv54m_-txXVVKpCoEULD6frvaRRhCIAfj0PWgY/edit#slide=id.g6e29efa84c_0_3), Jan 2020

## Run Labs from MyBinder with Jupyter Lab

- Browse to [mybinder.org](https://mybinder.org/)
- Enter repo URL, `https://github.com/rgstephens/rasa-days.git`, and click **launch**
- In the browser URL, change the last component from `tree` to `lab` to switch to Jupyter Lab

### Lab 1 - Create Moodbot with `rasa init`

- Open the `lab1.ipynb` workbook and step through the workbook
  - The first cell installs packages and starts the event loop
  - The `create_initial_project` call does the `rasa init` to create a new Rasa project
  - The next cell trains the model using the default moodbot training data
  - Run the last cell to talk to your bot, from the command line this is done with the `rasa shell` command

### Lab 2 - 

## Run Labs on Mac/Linux

```
git clone https://github.com/rgstephens/rasa-days.git
```