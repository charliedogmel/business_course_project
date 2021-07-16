# Business Fundamentals

# Question/need:

### What is the framing question of your analysis, or the purpose of the model/system you plan to build?

Which are the greatest areas of impact for community solar installations and improving building's energy efficiency? Develop a model to predict which census tracts to focus on to better utilize volunteer canvasing hours and financial resources. The purpose of the model is:

Predict or Identify: Given existing solar installation locations, which locations will be more likely to adopt solar? (From DeepSolar ML analysis, a relationship has already been established between proximity of existing solar panels and desire to install solar.)

Prescription: After finding these locations, filter the data for suitable rooftops for community solar.

https://10ay.online.tableau.com/t/melissametis/views/tableau-class/Dashboard1?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link

### Who benefits from exploring this question or building this model/system?

Energy for All - A program of GRID Alternatives:  GRID Alternatives is a national leader in community solar for low-income and underserved communities. The Energy for All program works to increase housing affordability and reduce the energy cost burden with single-family solar, community solar, and multifamily solar.

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


## Feedback:

- So you list a bunch of groups that could benefit from your project. But who is your main client? For whom are you doing this project, specifically? I think determining that will help you further determine the opportunity. What you have listed as your framing question is a little vague.

Bill & Melinda Gates Foundation
Grid U Washington
ITC - Investment Tax Credit: tax write-off for billionaires
Sun Run: helping them target where their sales efforts should go. I have a way to target customers who need this while bring down cost of customer acquisition while targeting people who need it most. Take credit for improving local air quality, helping disadvantaged communities and fulfilling your corporate social responsibility.
Trane, Carrier/Rheem, AO Smith: pitch to air/water heat pump company on who to target for home electrification (already existing solar homes)
Energy for All - A program of GRID Alternatives:  Develop a model to predict which neighborhoods to focus on and canvas to better utilize volunteer hours and 

- Yesterday, when I was going through the features, what I was doing was trying to identify a specific opportunity, and was doing that based on what I thought it would be useful to predict. What features would you focus on? I don't think that has been resolved here.

- You say you will "Predict the economic and environmental benefits to a high solar adoption rate," but I'm not sure what that means. How does that translate into some kind of data science model?

- I think it would help to specifically write out the opportunity, impact, impact hypothesis, and data science solution path and we can iterate on those. We can keep working on this in 1:1s if that would help!

Opportunity
Bring solar power and lower energy bills to low-income households via community shared solar projects.

"Community or shared solar is broadly defined as a project where multiple participants own or lease shares in a mid-sized solar facility, usually between 500 kilowatts and 5 megawatts, and receive credits that lower their monthly utility bills based on how much power the facility delivers to the grid."
"Many American households and businesses do not have access to solar because they rent, live in multi-tenant buildings, have roofs that are unable to host a solar system, or experience some other mitigating factor."
"Community solar expands access to solar for all, including in particular low-to-moderate income customers most impacted by a lack of access, all while building a stronger, distributed, and more resilient electric grid."

Impact


Impact Hypothesis


Data Science Solution Path

Using data from Project Solar, map the rooftops with