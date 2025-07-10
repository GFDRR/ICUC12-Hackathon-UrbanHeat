# Urban Heat Resilience Hackathon @ ICUC12

As part of the International Conference on Urban Climate ([ICUC12](https://icuc12.eu/)), the World Bank-GFDRR team under the Global Program on Urban Heat Resilience and the City Resilience Program, [@matthiasdemuzere](https://github.com/matthiasdemuzere), hosted a hands-on hackathon focused on urban heat resilience. We designed a set of challenges across three spatial scales: city, neighborhood, and building, and provided curated datasets for Timbuktu (Mali) and Davao (Philippines).

Participants were invited to explore these datasets using starter code based on our own workflows. The goal: develop scalable and actionable tools to support climate adaptation and urban planning.

Whether it's identifying locally effective cooling interventions or helping a mayor make the case for heat shelters, this repository holds everything used in the hackathon:

* Ready-to-run Python notebooks
* Open-source urban datasets 
* Real-world challenge descriptions
* Tools for modeling, analysis & visualization


### 💡 How to Use This Repository ?

* Start with the documentation, under the `docs/` folder. Begin with:
  * The motivation behind the project
  * A general overview of the hackathon setup
  * Details about the input datasets used

* Explore the notebooks

Notebooks are organized by spatial scale and model type (city, neighborhood, building). Each notebook loads helper functions from the `functions/` folder.

* Running the notebooks

All notebooks are designed to run smoothly in Google Colab. They should also work in other environments, just make sure to adjust the `BASE_DIR` path in the section labeled “Section to adjust” to reflect your own file structure, pointing to the data that is available as .zip per city under `data/`

We hope this repo inspires further innovation in tackling urban heat stress. Feel free to fork, adapt, and contribute!

