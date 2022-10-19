Data behind the plot
================
Alena Witzlack-Makarevich
2022-10-15

# Data set, data matrix, tabular data

-   A data set (or dataset) is a collection of data.

-   Most commonly datasets come in the tabular format and correspond to
    the contents of a single database table, or a single statistical
    data matrix

-   The term data set may also be used more loosely, to refer to the
    data in a collection of closely related tables, corresponding to a
    particular experiment or event.

-   every column represents a particular variable (height, weight,
    number of letters, number of vowels, …)

-   each row/record corresponds to a given member of the data set in
    question (e.g. a person, a sentence, a language, a phoneme, a
    measurement, …)

-   Every record shares the same set of variables.

-   In other words: Every row has the same set of column headers.

-   Tabular data are inherently rectangular and cannot have “ragged
    rows”.

-   If any row is lacking information for a particular column a missing
    value (NA) must be stored in that cell.

-   Each value (each cell) is known as a datum.

# Tabular data

![Variables and observations in a table](table_example.png)

------------------------------------------------------------------------

# Case study: Come fly with me

Which airlines should you travel with – and which should you avoid? We
sift through the data so you don’t have to (JAMES TOZER \| APRIL/MAY
2016)

-   <https://www.1843magazine.com/travel/what-the-numbers-say/come-fly-with-me>

> > > Asia’s airlines are mostly excellent; Europe’s are competent;
> > > America’s are awful. It is a pattern that many globetrotters have
> > > observed, but which we have confirmed by trawling through data on
> > > 18 major international carriers.

> > > We used flight-volume data from FlightStats.com and
> > > customer-satisfaction data from Skytrax, an airline consultancy
> > > which asks users to mark carriers out of five for the quality of
> > > their food, service, comfort, in-flight entertainment and value
> > > for money. American and United each scored 2.17 – barely half as
> > > much as leaders ANA and Singapore Airlines, both rated at 4.17.

> > > For prices, we took the world’s 30 busiest airports in the last
> > > quarter of 2015, and analyzed direct flights between them on
> > > week-long return trips from a sample at the start of August 2016.
> > > Most of the 870 routes we looked at had a cheapest option, but
> > > across the whole sample few companies were able to charge much
> > > more or less than their rivals – as you would expect in a
> > > competitive market.

> > > With so little difference in prices between airlines, the savvy
> > > traveller might as well opt for the comfiest seats, not the
> > > cheapest ones – and plump for Asian luxury over shoddy American
> > > service.

-   Which airlines should you travel with – and which should you avoid?
-   We sift through the data so you don’t have to Asia’s airlines are
    mostly excellent; Europe’s are competent; America’s are awful.
-   For prices, we took the world’s 30 busiest airports in the last
    quarter of 2015, and analyzed direct flights between them on
    week-long return trips from a sample at the start of August 2016.

Sketch the data matrix which could have been used to produce this plot:

![International airlines price vs service](international_airlines.png)

------------------------------------------------------------------------

Recall “Aesthetics”:

> > > aesthetic \< Gr. aisthētikos \< aisthēta ‘perceptible things’ \<
> > > aisthesthai ‘perceive’

In statistical graphics (specifically in the ggplot sense) this old
usage is meant: aesthetics are principles for relating sensory
attributes (color, shape, sound, etc.) to variables.

In modern usage (since mid 18th c., first in Ger. and then in Eng.),
aesthetics can also mean taste or beauty.

-   In a plot one aesthetic attribute can represent one variable

-   Sophisticated plots combine various aesthetic attributes (color,
    shape, line type, size, position, transparency, text, etc.) to
    represent multiple variables at ones

Which aesthetic attributes stand for what variable:

\_\_\_\_\_\_\_\_\_\_\_ represents \_\_\_\_\_\_\_\_\_\_\_\_

\_\_\_\_\_\_\_\_\_\_\_ represents \_\_\_\_\_\_\_\_\_\_\_\_

\_\_\_\_\_\_\_\_\_\_\_ represents \_\_\_\_\_\_\_\_\_\_\_\_

\_\_\_\_\_\_\_\_\_\_\_ represents \_\_\_\_\_\_\_\_\_\_\_\_

\_\_\_\_\_\_\_\_\_\_\_ represents \_\_\_\_\_\_\_\_\_\_\_\_

# More resources

-   <https://www.1843magazine.com/data-graphic/what-the-numbers-say/higher-earning>

-   <https://www.economist.com/1843/2016/05/06/where-to-buy>

-   <https://pudding.cool/2020/02/authors/>

-   <https://pudding.cool/2020/10/kpop/>

-   <https://pudding.cool/2018/08/filmordigital/>

-   <https://pudding.cool/2019/02/dress-code-sexualization/>

-   <https://pudding.cool/projects/vocabulary/>

-   <https://pudding.cool/2019/10/laugh/>

-   <https://pudding.cool/2017/03/film-dialogue/>

-   <https://pudding.cool/2019/05/names-in-songs/>

-   <https://pudding.cool/2019/11/big-hair/>

-   <https://pudding.cool/2017/08/screen-direction/>

-   <https://pudding.cool/2019/04/vogue/>