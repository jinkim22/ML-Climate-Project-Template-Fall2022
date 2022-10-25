Week 3

Wind
 global winds caused from differences in absorption of solar energy between the climate zones on Earth.

The two main causes of large-scale [atmospheric circulation](https://en.wikipedia.org/wiki/Atmospheric_circulation)qnd the rotation of the planet ([Coriolis effect](https://en.wikipedia.org/wiki/Coriolis_effect)
).

- Winds have various aspects:
    - [velocity](https://en.wikipedia.org/wiki/Velocity) ([wind speed](https://en.wikipedia.org/wiki/Wind_speed))
    - Density of the gas involved
    - energy content, or [wind energy](https://en.wikipedia.org/wiki/Wind_energy)
- Indirect effects
    - wildfires
    - dispersing seeds
    - flying insects / bird population
    - bad for livestock if it’s cold wind
        - when wind is > 25 mph, hair and wool are ineffective so they die
    - animal behavior
- There’s different types of winds the higher up you go in the atmostphere. maybe this will effect air travel?
- measured by anemometers or propagation speed of ultrasound signals or by the effect of ventilation on the resistance of a heated wire
- .


Week 4
Found dataset for general weather of regions (wind , temperature, etc.), and CO2 Levels in the atmosphere.
Both are daily measurements from 1/1/1980.
Need to figure out how I want to define "wind volatiilty." Is it variation within the day? number of sudden gusts? what is it?
I think I'm leaning more towards number of sudden gusts if that data is predictable, OR I can talk about how the max wind speed
for a certain day is becoming increasingly faster. Average is definitely increasing from the quick data analysis I did in my
Jupyter notebook, but also, the number of days where there were strong winds (>40mph) is increasing.

I also spend this week thinking about what wind is strong wind. Though building codes universally is supposed to withstand
~100-120mph gusts, I want to define strong, inconvenient winds to be > 40mph as this can cause small structural damage and
make it difficult for humans to be outside.

Remaining task: Find more variables / features that relate to wind speeds. CO2 emission is (unsurprisingly) not a good
indicator for how fast the winds will be for a given day. They do correlate somewhat with max temperature, and precipitation
so there may need to be some work done in making a causal effect framework.

Week 5
did a lot of reading for preparing the tidbit presentation, but also tried to read it more in depth because the method it uses
is very similar to what I want to do for my research
Realizations: forecastring wind volatility is difficult because my goal is to show that there are sudden wind gusts that could
be dangerous for humans. Sudden strong wind gusts are not recorded unfortuantely. A better approach may be to think about what
environment allows for the most variability in wind. In other words, what factors allow for strong winds to get generated out
of thin air? What is the relationship between CO2 emissions and those factors?
To focus on a specific region, keep in mind that it owuld require regional CO2 emission data. Using the total CO2 emission in
the atmosphere would be incorrect because that's for the whole globe. It may be easier to talk about trends.
Todo: Research what allows for strong winds to get spun up, what type of strong wind events there are, and what variables are
involved. Then, research how that can be tied back to CO2 emission, or increasing heat.

Week 6
Read more of the reserach paper being used

Week 7
Made basic model for doing linear regression to predict precipitation as temperature / CO2 changes. Researched Clausis Clapeyron
and started drafting introduction and problem statement.