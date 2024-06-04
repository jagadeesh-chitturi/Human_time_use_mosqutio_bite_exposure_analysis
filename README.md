# Human_time_use_mosqutio_bite_exposure_analysis

<h3>This is a partial analysis. I will be sharing the complete analysis once the Research Paper is published.</h3>

<h4>Contents</h4>
- This repo has four important files, two Python notebooks, and two PDF files of the same notebooks, which are used to analyze the visuals as they were created.
<b>Note:</b> A Few cells in the Python notebooks are removed to protect the privacy of the Research work and will be shared once the Paper is published
<br>
<hr>
<h3>1. <b></b>mosq_X_human_ATUS.ipynb</b> analysis of human exposure to mosquito bytes </h3>

<body>
<b> The main objective of this analysis is to find the relation between Human time use data from Bureau Labor Statistics and Mosquito blood meal patterns.
  Understanding and finding the hidden patterns of humans' exposure to mosquito bites based on different features (factors) like humans working conditions in indoor/outdoor jobs, based on race and ethnicity background, Gender of human, and Income level of people.</b>
    <br><br>
    In our study, we primarily examined individuals in outdoor jobs. This choice was driven by the understanding that these individuals are more likely to be exposed to mosquito bites than those in indoor occupations.
    <br>
    <ul>
    <li> We use different races like NH white, Hispanic, NH black, and others</li>
    <br>
    <li>Male and female in gender category</li>
    <br>
    <li> Income level into low, average, and High-income groups</li>
    <br>
   <li> We mainly concentrated on two mosquito types (Aedes aegypti and Culex quinquefasciatus) as different mosquito species have different preferences for the day/night when they actively seek blood meals.</li>
        </ul>
</body>
<body> The below plot represents the normal time use of most humans for 24 hours of the day, which implies that humans mostly come out during the day</body>

![image](https://github.com/jagadeesh-chitturi/Human_time_use_mosqutio_bite_exposure_analysis/assets/117065124/5ef9039c-ee2b-4d38-b491-b37307a33845)

<body> The below are the plots that show the mosquito activity for 24 hours of day</body>

![image](https://github.com/jagadeesh-chitturi/Human_time_use_mosqutio_bite_exposure_analysis/assets/117065124/63ae7678-0548-4ce8-b02b-a33f278d418c)

<b> Conclusion: So this shows that these mosquito types are most active during the early hours of the morning and late hours in the evening</b>

<br>
<hr>
<h3>2. <b>bootstrap_atus_analysis_partial.ipynb</b> analysis of human time use on various features depending on weekday or weekend </h3>
<body>Like from the below figure, we can infer that Males spend more time outdoors than females</body>

![image](https://github.com/jagadeesh-chitturi/Human_time_use_mosqutio_bite_exposure_analysis/assets/117065124/27395d06-29af-4316-8eb5-6cda38f70d8b)

<body> The below plot shows that High-income people spend more time outdoors than others on weekends, which makes sense</body>

![image](https://github.com/jagadeesh-chitturi/Human_time_use_mosqutio_bite_exposure_analysis/assets/117065124/1594b1f4-3d5d-4e7a-9f15-02b397af0c0e)
