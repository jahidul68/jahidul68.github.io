---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
    <h1>San Francisco's Fight Against Drugs</h1>
    <p>In the heart of the Bay Area, San Francisco has recently been a focal point in the national conversation on
    drugs, crime and overdose. [1][2] The city's unique geography, diverse population, and vibrant culture have shaped its drug
    landscape, with a complex interplay of factors influencing drug-related incidents over the years.
    Our analysis dives into the data to uncover trends, patterns, and insights that shed light on
    San Francisco's ongoing battle against drugs.</p>
    <p>The data we used, available through DataSF's open data initiative [3], encompasses over 2.13 million rows, each a
    distinct incident report detailing the specifics of crime occurrences across the city. The attributes range
    from incident numbers, categories, descriptions, dates and times, to locations,
    which paints a comprehensive picture of drug related crime dynamics in the city.</p>

<div style="display: flex; justify-content: center; align-items: center; font-family: Georgia, 'Times New Roman', Times, serif;">
    <div style="width: 100%; text-align: center;">
        <iframe src="/static/Notebook.html" width="100%" height="465" frameborder="0"></iframe>
        <p style="font-style: italic;">Drug/Narcotic rate decreasing over the years.</p> <p style="color: #808080;">Although the data for June-December for 2018 isn't available, it's clear that the trend has been downwards for the last few years</p>
        </div>
</div>

</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
    <p>San Francisco was once notorious for its high incidence of drug-related cases, prompting the state to
    introduce numerous initiatives aimed at reversing the trend. Recent efforts have proven successful, with a
    noticeable decline of crimes. Analysis of the data reveals a consistent upward trajectory in the rates from
    the early 2000s to the 2010s, followed by a significant downturn in recent years, where lighter shades indicates
    lower incident counts. This trend suggests a positive shift in the city's drug landscape, possibly due to a
    combination of factors such as <a href="https://www.kqed.org/stateofhealth/363143/san-franciscos-newest-tool-to-prevent-opioid-overdoses-tests-drugs-starts-conversations">
    raising awereness</a>, law enforcement strategies [7], community programs [6], and changes in drug usage behaviors.</p>


    <p>Furthermore, the heatmap does not reveal any distinct seasonal patterns in drug usage, with the data showing a
    somewhat consistent distribution of activities throughout the year. This uniformity suggests that external
    factors like weather conditions do not significantly influence the occurrence of drug-related crimes, which could
    be explained by the geographical position of San Francisco and its relatively stable climate throughout the year.</p>

</div>

<div style="display: flex; justify-content: center; align-items: center; font-family: Georgia, 'Times New Roman', Times, serif;">
    <div style="width: 100%; text-align: center;">
        <iframe src="/static/lineplot.html" width="600" height="450" frameborder="0"></iframe>
        <p style="font-style: italic;">Specific drugs (marijuana, cocaine, heroin, methamphetamine, prescription drugs/opioids) related incidents decreasing over the years.</p>
        <p style="color: #808080;">Please note that the data for June-December for 2018 isn't available, making this year
        appear to have a lower number of incidents than it actually does.
        </p>
    </div>
</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
    <p>To paint a more nuanced picture of the drug issues, we display the evolution of incidents that relate
    to San Francisco's most prevalent drugs - cocaine, heroin, methamphetamine, prescription drugs, and marijuana.
    Of these, cocaine stood out for its significant presence in the city, with the highest number of incidents reported
    over the years. However, a clear trend of a steady decline involving all the substances is evident, indicating
    that the city's efforts to combat drug-related crimes have been effective for a range of different substances.

    </p>


    <p>A particularly intriguing aspect of San Francisco's drug narrative is the story of marijuana. Once a major driver
    of drug-related incidents, marijuana's path reflects a broader shift in societal and legal attitudes.
    The legalization of marijuana in California, marked by Proposition 64 in 2016 [8], catalyzed a dramatic shift, not
    just in legal terms but also in its impact on drug incident reports. Post-legalization, the data hints at a
    diminished role for marijuana in the city's drug incident landscape, likely due to the removal of legal
    penalties for possession and use, coupled with regulated access.</p>.
</div>

<div style="display: flex; justify-content: center; align-items: center; font-family: Georgia, 'Times New Roman', Times, serif;">
    <div style="width: 100%; text-align: center;">
        <iframe src="/static/category.html" width="600" height="700" frameborder="0"></iframe>
        <p style="font-style: italic;">Comparison of the two most prevalent drugs: Cocaine and Marijuana, across various San Francisco areas.</p>
    </div>
</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
    <p>
        In our investigation into San Francisco's drug scene, we further
        dissected the data to explore whether the specific drugs involved in incidents exhibit distinct spatial patterns.
        We've focused on the two most significant substances:
        cocaine and marijuana. The data,
        presented in a logarithmic scale, highlights a distinct pattern: both cocaine and marijuana-related
        incidents are more prevalent in the central areas of San Francisco. Cocaine incidents, in particular,
        exhibit a pronounced concentration in specific neighborhoods, while marijuana-related offenses sprawl
        more widely across the city.
    </p>

    <p>
        Of particular interest is the Tenderloin area, which stands out for its disproportionately high incidence of drug-related crimes across various substances. Over the years, economic struggles have plagued this neighborhood, dating back to the 1960s, leading to pervasive poverty. Known for its open-air drug markets, it has gained notoriety as a hub for drug-related activities. This reputation underscores the area's significance in the realm of drug-related incidents. Moreover, a striking statistic emphasizes its impact: only 53% of individuals apprehended for substance-related offenses during targeted drug market interventions actually reside in San Francisco, highlighting the pervasive issues associated with drug markets in the area. [4][5]
    </p>

</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
<h2>References</h2>
<p>1. <a href="https://www.nytimes.com/2024/01/31/briefing/san-francisco-addiction.html">New York Times: San Francisco’s “Pro-Drug Culture” </a></p>
<p>2. <a href="https://www.sfchronicle.com/projects/san-francisco-drug-overdose-deaths/#:~:text=San%20Francisco%20continues%20to%20grapple,of%20the%20synthetic%20opioid%20fentanyl.">San Francisco Chronicle: Drug Overdose Deaths in San Francisco</a></p>
<p>3. <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">San Francisco Crime Dataset</a></p>
<p>4. <a href="https://www.wbur.org/onpoint/2022/11/02/tenderloin-reality-of-the-drug-trade-in-san-francisco">The reality of the drug trade in San Francisco </a></p>
<p>5. <a href="https://www.sf.gov/news/san-francisco-releases-new-numbers-showing-almost-half-those-cited-public-drug-use-dont-live">San Francisco Releases New Numbers Showing Almost Half of those Cited for Public Drug Use Don't Live in the City </a></p>
<p>6. <a href="https://www.brennancenter.org/our-work/analysis-opinion/community-organizations-have-important-role-lowering-crime-rates">Community Organizations Have an Important Role in Lowering Crime Rates </a></p>
<p>7. <a href="https://www.sf.gov/news/san-francisco-issues-six-month-update-operation-dismantle-open-air-drug-markets">Operation to Dismantle Open-Air Drug Markets </a></p>
<p>8. <a href="https://www.courts.ca.gov/prop64.htm#:~:text=Effective%20November%209%2C%202016%2C%20Proposition,sealing%20of%20prior%2C%20eligible%20marijuana%2D">Proposition 64 </a></p>

<h2>Contributions</h2>
<p>Ting Hui Cheng (s232855): Map plot + text</p>
<p>Lukas Rasocha (s233498): Interactive Bokeh plot + text </p>
<p>Md Jahidul Islam (s240010): Heatmap + text </p>
</div>
