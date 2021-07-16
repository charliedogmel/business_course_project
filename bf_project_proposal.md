# Business Fundamentals

# Question/need:

### What is the framing question of your analysis, or the purpose of the model/system you plan to build?

Which are the greatest areas of impact for community solar installations and improving building's energy efficiency? Develop a model to predict which census tracts to focus on to better utilize volunteer outreach hours and financial resources of the non-profit GRID Alternatives. It will also use the census tract's dominant heating fuel and number of heating days to determine which areas use natural gas that would benefit from energy efficiency upgrades like electric heat pumps.

The purpose of the model is:

Predict or Identify: Given existing solar installation locations, which locations will be more likely to adopt solar? (From DeepSolar ML analysis, a relationship has already been established between proximity of existing solar panels and desire to install solar.)

Prescription: After finding these locations, filter the data for suitable rooftops for community solar. ("Community or shared solar is broadly defined as a project where multiple participants own or lease shares in a mid-sized solar facility, usually between 500 kilowatts and 5 megawatts, and receive credits that lower their monthly utility bills based on how much power the facility delivers to the grid."
"Many American households and businesses do not have access to solar because they rent, live in multi-tenant buildings, have roofs that are unable to host a solar system, or experience some other mitigating factor."
"Community solar expands access to solar for all, including in particular low-to-moderate income customers most impacted by a lack of access, all while building a stronger, distributed, and more resilient electric grid.")

Opportunity
Bring solar power and lower energy bills to low-income households via community shared solar projects and energy efficiency upgrades where possible.

### Who benefits from exploring this question or building this model/system?

Energy for All - A program of GRID Alternatives:  GRID Alternatives is a national leader in community solar for low-income and underserved communities. The Energy for All program works to increase housing affordability and reduce the energy cost burden with single-family solar, community solar, and multifamily solar.

Households and businesses who rent, live in multi-tenant buildings, have unsuitable roofs, or some other reason will benefit from lower monthly utility bills. Low-income households spend a disproportionate amount of income, 8.5%, on utilities.

Climate change

# Data Description:

### What dataset(s) do you plan to use, and how will you obtain the data?

Google Project Sunroof data explorer - https://sunroof.withgoogle.com/data-explorer/ - is a publicly available dataset that shows solar potential and impact for portions of the US.

DeepSolar by Stanford - http://web.stanford.edu/group/deepsolar/home.html# - is a publicly available database of solar installations in the contiguous US and includes socioeconomic characteristics, location, size, and type information for each recorded solar power system.

Both datasets area easily downloaded into csv format along with the metadata.

### What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?

I will work with region, number of buildings suitable for solar, number of buildings that already have solar, solar energy generation potential, potential CO2 abatement,  household income, electricity rate, electricity consumption, latitude, longitude, gini index, heating fuel used.

### If modeling, what will you predict as your target?

Predict and map the locations that are underserved, have viable roof space, and will be more receptive to adopting solar, as well as the amount of money that residents would save.

# Tools:

### How do you intend to meet the tools requirement of the project?

Use Google Sheets and Tableau for EDA and Tableau for visualization.

### Are you planning in advance to need or use additional tools beyond those required?

No

# MVP Goal:

### What would a minimum viable product (MVP) look like for this project?

Some exploratory plots and a preliminary presentation.


#### Main client brainstorming:

Bill & Melinda Gates Foundation

Grid U Washington

ITC - Investment Tax Credit: tax write-off for billionaires

Sun Run: helping them target where their sales efforts should go. I have a way to target customers who need this while bring down cost of customer acquisition while targeting people who need it most. Take credit for improving local air quality, helping disadvantaged communities and fulfilling your corporate social responsibility.

Trane, Carrier/Rheem, AO Smith: pitch to air/water heat pump company on who to target for home electrification (already existing solar homes)

Energy for All - A program of GRID Alternatives:  Develop a model to predict which neighborhoods to focus on and canvas to better utilize volunteer hours and 

Complication: Why do community solar and energy efficiency upgrades together? Most renters don't have control over their building to make energy efficiency changes.