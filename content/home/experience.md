+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 60  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Fellow"
  company = "Information Extraction and Synthesis Laboratory (IESL)"
  company_url = "http://www.iesl.cs.umass.edu/"
  location = "Massachusetts"
  date_start = "2020-06-29"
  date_end = ""
  description = """
  The role allows me to pursue projects with the IESL lab members. In addition, I contribute to OpenReview, the open-access, open-discussion conference platform. I also work with the Chan Zuckerberg Initiative to apply IESL's lab output to CZI's systems and databases.
  
  Tasks:

  * Case-based reasoning for knowledge base completion and question answering.
  * Incorporated a language model based system trained on citation and authorship graphs into [OpenReview Expertise](https://github.com/openreview/openreview-expertise) which generates affinity scores between submitted papers and available reviewers. This system generates affinity scores between submitted papers and available reviewers' past body of work.
  * Added features to the fairness-constrained matching algorithms of [OpenReview Matcher](https://github.com/openreview/openreview-matcher), which solve an optimization problem to assign papers for review given pre-computed affinity scores. The "fair" matching algorithms ensure that the reviewers assigned to every submission possess a (combined) minimum level of familiarity with the research area.
  * Currently working to scale an affiliation disambiguation system to **400K+** target affiliation labels as part of IESL's collaboration with the [Meta-CZI](https://www.meta.org/).
  """

[[experience]]
  title = "Machine Learning Intern"
  company = "SRI International"
  company_url = "https://www.sri.com/"
  location = "California"
  date_start = "2019-05-20"
  date_end = "2019-08-23"
  description = """
  Member of a team of researchers from the [Artificial Intelligence Center (AIC), SRI International](https://www.sri.com/about/organization/information-computing-sciences/aic) participating in the DARPA program: [Radio Frequency Machine Learning Systems (RFMLS)](https://www.darpa.mil/program/radio-frequency-machine-learning-systems)
  
  Tasks:

  * Developed and maintained an RF spectrum simulator for fast and reproducible experimentation.
  * Implemented and benchmarked reinforcement learning approaches to control/steer an antenna array for RF monitoring.
  * Experimented with alternative training regimes such as imitation learning. This method led to better performance than the available baselines.
  """

[[experience]]
  title = "Software Development Intern"
  company = "Centre for Development of Advanced Computing (CDAC)"
  company_url = "https://www.cdac.in/"
  location = "Pune, India"
  date_start = "2016-05-09"
  date_end = "2016-07-22"
  description = """
  * Studied and implemented the principles of parallel processing using MPI and OpenMP.
  * Contributed to a molecular dynamics simulator capable of leveraging the compute capabilities of a CPU cluster. The simulator implemented distributed computation of the physics of particle movement.
  """

+++
