# Green IT

Green IT, also known as green computing, is the practice of environmentally sustainable computing.

At any rate, the first step is to measure emissions

This document aims to outline the process of becoming aware of CHORUS's energy consumption.

## (Not so fun) Facts

1. Rebound effect/Jevons paradox: Increased efficiency induces increase in demand enough that resource use is increased, rather than reduced.
2. Annual Carbon Footprint per person/year
  - *Data Scientist: 40 tCO2* (source Loïc Lannelongue/green algorithms)
  - *IPCC target: 2 tCO2* (Intergovernmental Panel on Climate Change)
  - *Swiss citizen: 14 tCO2* (Source swissinfo)
3. 65 tCO2e / publication (source EMBL)
4. "Yeah so, the idea that, somehow, Al is an environmental disaster in the making? Total BS!" Yann LeCun
5. Environmental impact of computing
  - Life-cycle footprint of the hardware (>82% of the 54m of tonnes of e-waste are handled by 12-56m informal waste workers worldwide)
  - Long-term data storage
    - UK Biobank: 15 PB by 2025
    - First picture of a black hole: 5 PB
  - Powering the computer
    - A medium-sized data centre (15 MW) uses as much water as three average-sized hospitals

## Formula  
The carbon footprint of an algorithm depends on two factors: the energy needed to run it and the pollutants emitted when producing such energy. The former depends on the computing resources used (e.g., number of cores, running time, and data center efficiency) while the later, called carbon intensity, depends on the location and production methods used (e.g., nuclear, gas, or coal).

Carbon footprint (gCO2e) = energy used (kWh) * carbon intensity (gCO2e/kWh)

## Resources

- Existing Measurement Tools
  - [carbontracker](https://github.com/lfwa/carbontracker.git): Track and predict the energy consumption and carbon footprint of training deep learning models. 
  - [Green Algorithms](https://www.green-algorithms.org/): Online tool called for estimating the carbon footprint of computational tasks. It considers factors like hardware, runtime, and data center location and energy sources. 
  - [Code Carbon](https://pypi.org/project/codecarbon/): Estimate and track carbon emissions from your computer, quantify and analyze their impact. 
  - [experiment-impact-tracker](https://github.com/Breakend/experiment-impact-tracker) simple drop-in method to track energy usage, carbon emissions, and compute utilization of your system. 
  - [Cloud Carbon Footprint](https://www.cloudcarbonfootprint.org/) Free and Open Source Cloud Carbon Emissions Measurement and Analysis Tool
  - [tracarbon](https://github.com/fvaleye/tracarbon) Tracarbon tracks your device's energy consumption and calculates your carbon emissions using your location.
  - [cumulator](https://pypi.org/project/cumulator/) A tool to quantify and report the carbon footprint of machine learning computations and communication in academia and healthcare
- Articles
  - [Green Algorithms: Quantifying the Carbon Footprint of Computation](https://doi.org/10.1002/advs.202100707)
  - [Training a single AI model can emit as much carbon as five cars in their lifetimes](https://www.technologyreview.com/2019/06/06/239031/training-a-single-ai-model-can-emit-as-much-carbon-as-five-cars-in-their-lifetimes/)
  - [Deep Learning’s Carbon Emissions Problem](https://www.forbes.com/sites/robtoews/2020/06/17/deep-learnings-climate-change-problem/)
  - [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? ](https://dl.acm.org/doi/10.1145/3442188.3445922)
    - [LEAF - A New Approach to Achieving Laboratory Sustainability](https://www.sustainabilityexchange.ac.uk/leaf_a_new_approach_to_achieving_laboratory_sus)
    - [Power Hungry Processing: Watts Driving the Cost of AI Deployment?](https://arxiv.org/abs/2311.16863)
    - [Carbon footprint estimation for computational research](https://www.nature.com/articles/s43586-023-00202-5)
- Communities: 
  - [2023 Workshop resources](https://www.eicworkshop.info/#resources) on environmental impacts of computing in health & life sciences research
  - [Join an upcoming community of practice](https://forms.gle/rgeqzcpo51gge5Xr6) from Green Algorithms
  - [LEAF - Laboratory Efficiency Assessment Framework](https://www.ucl.ac.uk/sustainable/take-action/staff-action/leaf-laboratory-efficiency-assessment-framework)
- Other
  - [Electricity Map, Climate Impact by Area](https://app.electricitymaps.com/map)
  - [Digital Ethics Canvas 2023 - Software Design](https://docs.google.com/document/d/1lhGV_xJiiuC98it5RB2TiitIBgu0pjUK8qq-8y-wbPw/edit#heading=h.3oqqml7cc03h) from [Fairness in Machine Learning](https://docs.google.com/presentation/d/1x1ZWUPWWT8f2z8VkqedKOSUHBH9T9RtcyiwOkySBgV8/edit#slide=id.g250abee30ad_0_140)


# Q&A

## Output
 - How do we communicate ? 
  - CO2 Sequestration by Trees
  - Units, comparison, etc. ?


## Measures
- How do we measure?
  - Computing
  - Storage
  - Hardware 
- Asks our provider to supply measures

This document was started at [AMLD2024](2024.appliedmldays.org) at the "Environmentally Sustainable AI" track, and is a growing and collaborative effort. Contributions are welcome.


