# {PROJECT NAME}

## Summary 

**{PROJECT NAME}** is a Jupyter Notebook and Python application that *does something*

## Input
- describe what is needed 

## Output
(example from quiz-reports)
### `.zip` file containing a PDF per student _(who submitted the quiz)_

- **ID** (randomly-generated, anonymous student identifier)
- **Course name** (as it appears on Canvas)
- **Question text** (as it appears on Canvas)
- **Student's response** (all submitted text -- does not preserving formatting)

> NOTE: all of the above will repeat for as many questions as are in the quiz (on seperate pages)

### `.csv` detailing

- **Student Name** (as it appears on Canvas)
- **Student ID** (UBC student ID)
- **Canvas ID** (Canvas LMS ID)
- **Anonymous ID** (as it appears in the output PDFs)

> NOTE: this table contains sensitive information and should **NOT** be distributed or uploaded anywhere

## Important Caveats

- what would make this NOT WORK? 

## Getting Started

_Are you Sauder Operations Staff? Please go [here](sauder-ops-guide.md) for detailed instructions_

> Project uses **conda** to manage environment (See official **conda** documentation [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file))

1. Clone **PROJECT** repository

1. Install [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) (Python 3.7 version)

1. Import environment: `$ conda env create -f environment.yml`

1. Run:
   1. `$ conda activate ENV_NAME`
   1. `$ jupyter notebook`
   1. Select **Kernal** > **Restart & Run All**
