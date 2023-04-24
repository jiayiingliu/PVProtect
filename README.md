
# PVProtect

PVProtect is a new software that falls within the domain of renewable energy technology, to be more specific, within the area of solar panel technology. 

Everybody knows what solar panels are. They are juts devices that convert sunlight into electricity. They are made of photovoltaic cells and they have become very popular in recent years as people look for more sustainable sources of energy. 

However, they lose their efficiency dramatically over time. For this reason, we have developed PV Protect, which will activate or deactivate the solar panels according to the energy needs of the house.

As mentioned, the technology implemented will decide to activate or deactivate the solar panels according to 4 real time factors:
- Battery level (if it has one)
- The consumption 
- Production

So, the key point here is that the algorithm is designed so that the amount of time the PV panel is turned ON is minimized while the self consumption is maximized.

To achieve this, we have built an optimization model with different weights for the different factors mentioned before. 
In light of the above, if the production is below a certain threshold for a sustained period of time, the PV panel will be turned OFF.
Moreover, if we are producing much more than we are consuming and the batteries are fully charged, the PV panels will also be turned OFF. Otherwise we will be sending energy to the electric network.

On the other hand, the solar panels will be turned ON if the battery is not fully charged or if the consumption is slightly lower than the production (we will be sending a small amount of energy to the electric network, which is not a huge problem)

It is important to remember that we are aiming to minimize the usage of the panels while maximizing the self consumption. 

Overall, we have created a software that will switch on and off the solar panels to prolong their lifespan and efficiency.


## On which users is our software focused?
- Citizens
- Companies
- Factories

Nowadays, people or companies who use solar panels have increased a lot, since it has many advantages such as:
- The energy provided is totally ecologic, so sustainability is one of the factors that gives valor to this energy system because it decreases the emission of gasses and other pollutants which could contaminate the environment.
- It could adapt to any type of users according to their necessity.
- Save money


The users could interact with our software through an application. This application provides the following services:
1. Button to connect and disconnect the panel: the users could connect and disconnect by a click when necessary. This is not recommended since our software will make accurate decisions automatically to maximize self consumption as mentioned before.
2. Data about how much energy is produced by the panels and how much is consumed.
3. % energy provided by the Solar Panel
4. % energy provided by the electric network
5. Create a warning when there is a drop of efficiency. Meaning that there may be some dust or other particles in front the PV panel 
6. Button to disconnect the panel when there is a fire emergency.
7. Amount of money saved by using the solar panels
8. Times of the day the panel was ON or OFF
9. Tell is the panels are activated right now
10. % energy from the solar panel that is consumed (should be as high as possible)
11. % of energy that is sent to the electric network (should be as low as possible)
12. Measure of the evolution of the performance of the panel.



# Contact

Authors: Jiaying Liu, Pablo Perez, Ilia Lecha, Lluís Giménez

Mails: 

Task Board: https://trello.com/b/3yEjjdTZ/task-board-tool






