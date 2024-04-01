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
        <p style="font-style: italic;">Drug/Narcotic rate decreasing over the years.</p>
        <p style="font-color: gray; font-size: 8px;"> Although we don't have the data for June-December for 2018, it's clear that the trend is downwards for the last few years</p>
    </div>
</div>

</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
    <p>San Francisco was once notorious for its high incidence of drug-related cases, prompting the state to introduce numerous initiatives aimed at curbing the trend. Recent efforts have proven successful, with a noticeable decline of crimes. Analysis of the data reveals a consistent upward trajectory in the rates from the early 2000s to the 2010s, followed by a significant downturn in recent years, where lighter shades indicates lower incident counts. This trend suggests a positive shift in the city's drug landscape, possibly due to a combination of factors such as law enforcement strategies, community programs, and changes in drug usage behaviors. Furthermore, the heatmap does not reveal any distinct seasonal patterns in drug usage, with the data showing a somewhat consistent distribution of activities throughout the year. This uniformity suggests that external factors like weather conditions do not significantly influence the occurrence of drug-related crimes, which could be explained by the geographical position of San Francisco and its relatively stable climate throughout the year.</p>

    <p>Among the array of initiatives, employing diverse <a href="https://www.kqed.org/stateofhealth/363143/san-franciscos-newest-tool-to-prevent-opioid-overdoses-tests-drugs-starts-conversations">tools</a> and empowering law enforcement played pivotal roles in effectively controlling the trend.</p>
 master
    <p>Changes in socio-economic conditions and community development programs may have also contributed to the decrease in crime rates. Efforts to address poverty, unemployment, and inequality, as well as investments in education, affordable housing, and social services, can have a positive impact on crime prevention by addressing underlying social determinants of criminal behavior.</p>

    <p> Adoption of harm reduction strategies such as needle exchange programs and supervised injection sites could have mitigated the negative effects of drug abuse on the community. Implementation of policies targeting drug trafficking, along with legislative changes related to drug sentencing and promoting rehabilitation programs, may have had a positive impact on reducing drug-related crime rates. </p>
    <!-- Add more text here -->
 master
</div>

<div style="display: flex; justify-content: center; align-items: center; font-family: Georgia, 'Times New Roman', Times, serif;">
    <div style="width: 100%; text-align: center;">
        <iframe src="/static/lineplot.html" width="600" height="450" frameborder="0"></iframe>
        <p style="font-style: italic;">Specific drugs (marijuana, cocaine, heroin, methamphetamine, prescription drugs/opioids) related incidents decreasing over the years.</p>
    </div>
</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
    <p>Our exploration focuses on several key substances that have notably influenced the city's drug landscape: cocaine, heroin, methamphetamine, prescription drugs and marijuana. Of these, cocaine stood out for its significant presence, underscoring a nationwide concern that spans years. However, a clear trend of a steady decline in incidents involving these substances can be observed. This downward trajectory suggests a combination of successful law enforcement strategies, community engagement, and possibly, changes in drug usage behaviors. TRY TO FIND SOURCES</p>


    <p>A particularly intriguing aspect of San Francisco's drug narrative is the story of marijuana. Once a major driver of drug-related incidents, marijuana's path reflects a broader shift in societal attitudes and legal frameworks. The legalization of marijuana in California, marked by Proposition 64 in 2016, catalyzed a dramatic shift, not just in legal terms but also in its impact on drug incident reports. Post-legalization, the data hints at a diminished role for marijuana in the city's drug incident landscape, likely due to the removal of legal penalties for possession and use, coupled with regulated access.</p>.
</div>

<div style="text-align: justify; font-family: Georgia, 'Times New Roman', Times, serif;">
<h2>References</h2>
<p>1. <a href="https://www.nytimes.com/2024/01/31/briefing/san-francisco-addiction.html">New York Times: San Francisco’s “Pro-Drug Culture” </a></p>
<p>2. <a href="https://www.sfchronicle.com/projects/san-francisco-drug-overdose-deaths/#:~:text=San%20Francisco%20continues%20to%20grapple,of%20the%20synthetic%20opioid%20fentanyl.">San Francisco Chronicle: Drug Overdose Deaths in San Francisco</a></p>
<p>3. <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">San Francisco Crime Dataset</a></p>
</div>
