## COVID-19 Symptomatic Manifestation

<p align="center">
<img src="https://github.com/Berger-DM/berger-dm.github.io/COVID-19%20Process%20Models/COVID-19%20Symptomatic%20Manifestation.png" width=50% height=50%>
</p>

The Symptomatic Manifestation of COVID-19 Disease process starts when a person is infected (*Start Event: Person Infected*). The infection receptor, or infected receptor, then goes through the disease incubation period before manifesting any symptoms (*Intermediate Timer Event: Incubation period*). This period may range from 1 to 14 days in duration, with a mean duration of 5 to 6 days. After that, the disease may initially manifest with different severities (*Task: Determine initial severity of infection*). The initial severity can either be mild, moderate, or severe.

If the severity of the disease is mild, then the infected receptor goes through the mild symptomatic manifestation of the illness (*Subprocess: Mild illness symptomatic manifestation*). After that, it may either be fatal to them, or not. If it is fatal, the process ends with the person deceased (*End Event: Person deceased*). If not, they then go through the recovery period for mild or moderate cases (*Intermediate Timer Event: Recovery period for mild/moderate cases*). After that, the process ends with the infected receptor recovered from the infection (*End Event: Person recovered from infection*). While manifesting mild symptoms, the infected receptor may experience a worsening of their clinical condition (*Intermediate Boundary Error Event: Clinical Condition Worsened*). If they do, their condition may deteriorate to either severe or critical disease. If it deteriorates to severe disease, the infected receptor goes through the severe symptomatic manifestation of the disease, which is explained later in the process description. If they deteriorate to critical disease, they go through the critical symptomatic manifestation of the disease, which is explained later in the process description. 

If the severity of the disease is moderate, then the infected receptor goes through the moderate symptomatic manifestation of the disease (*Subprocess: Moderate Illness Symptomatic Manifestation*). After moderate illness manifests, it may either be fatal to them, or not. If it is, the process ends when the person is deceased (*End Event: Person deceased*). If not, they go through the recovery period for mild or moderate cases (*Intermediate Timer Event: Recovery period for mild/moderate cases*), and then the process ends when they are recovered from the infection (*End Event: Person recovered from infection*). While manifesting moderate symptoms, the infected receptor may experience a worsening of their clinical condition (*Intermediate Boundary Error Event: Clinical Condition Worsened*). If they do, their condition deteriorates to critical disease, and they go through the critical symptomatic manifestation of the disease, which is explained later in the process description. 

If the disease symptoms are severe, then the infected receptor goes through the severe manifestation of the disease (*Subprocess: Severe Illness Symptomatic Manifestation*). After severe illness manifests, it may either be fatal to them, or not. If it is, the process ends when the person is deceased (*End Event: Person deceased*). If not, they go through the recovery period for severe or critical cases (*Intermediate Timer Event: Recovery period for severe/critical cases*), and then the process ends when they are recovered from the infection (*End Event: Person recovered from infection*). While manifesting severe symptoms, the infected receptor may experience a worsening of their clinical condition (*Intermediate Boundary Error Event: Clinical Condition Worsened*). If they do, their condition deteriorates to critical disease, and they go through the critical symptomatic manifestation of the disease, which is explained later in the process description.

If the infected receptor deteriorates to critical disease, then they go through the critical symptomatic manifestation of the disease (*Subprocess: Critical Illness Symptomatic Manifestation*). After critical illness manifests, it may either be fatal to them, or not. If it is, the process ends when the person is deceased (*End Event: Person deceased*). If not, they go through the recovery period for severe or critical cases (*Intermediate Timer Event: Recovery period for severe/critical cases*), and then the process ends when they are recovered from the infection (*End Event: Person recovered from infection*).

<p align="center">
<img src="https://github.com/Berger-DM/SARS-CoV-2-COVID-19-Models/blob/gh-pages/COVID-19%20Process%20Models/Mild%20Illness%20Symptomatic%20Manifestation.png" width=50% height=50%>
</p>

In the mild symptomatic manifestation of the disease, the infected receptor may develop a range of mild symptoms. These may be dry cough (*Task: Develop dry cough*), mild fever (*Task: Develop mild fever*), nasal congestion (*Task: Develop nasal congestion*), sore throat (*Task: Develop sore throat*), headache (*Task: Develop headache*), muscle pain (*Task: Develop muscle pain*), malaise (*Task: Develop malaise/fatigue*), or other symptoms (*Task: Develop other mild illness symptoms*).

<p align="center">
<img src="https://github.com/Berger-DM/SARS-CoV-2-COVID-19-Models/blob/gh-pages/COVID-19%20Process%20Models/Moderate%20Illness%20Symptomatic%20Manifestation.png" width=50% height=50%>
</p>

In the moderate symptomatic manifestation of the disease, the infected receptor may develop a range of moderate symptoms. These may be fever (*Task: Develop fever*), cough (*Task: Develop cough*), shortness of breath (*Task: Develop shortness of breath*), tachypnea (*Task: Develop tachypnea*), or other symptoms (*Task: Develop other moderate illness symptoms*).

<p align="center">
<img src="https://github.com/Berger-DM/SARS-CoV-2-COVID-19-Models/blob/gh-pages/COVID-19%20Process%20Models/Severe%20Illness%20Symptomatic%20Manifestation.png" width=50% height=50%>
</p>

In the severe symptomatic manifestation of the disease, the infected receptor may develop a range of severe symptoms. These may be severe pneumonia (*Task: Develop severe pneumonia*), ARDS (*Task: Develop acute respiratory distress syndrome*), sepsis (*Task: Develop sepsis*), septic shock (*Task: Develop septic shock*), or other symptoms (*Task: Develop other severe illness symptoms*).

<p align="center">
<img src="https://github.com/Berger-DM/SARS-CoV-2-COVID-19-Models/blob/gh-pages/COVID-19%20Process%20Models/Critical%20Illness%20Symptomatic%20Manifestation.png" width=50% height=50%>
</p>

In the critical symptomatic manifestation of the disease, the infected receptor may develop a range of critical symptoms. These may be respiratory failure (*Task: Develop respiratory failure*), RNAemia (*Task: RNAemia*), cardiac injury (*Task: Develop cardiac injury*), septic shock (*Task: Develop septic shock*), Multiple Organ Dysfunction (*Task: Develop multiple organ dysfunction*), or other symptoms (*Task: Develop other critical illness symptoms*).
