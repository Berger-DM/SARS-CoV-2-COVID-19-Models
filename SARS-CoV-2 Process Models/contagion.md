## SARS-CoV-2 Contagion

<p align="center">
<img src="https://github.com/Berger-DM/SARS-CoV-2-and-COVID-19-Process-Models/blob/gh-pages/SARS-CoV-2%20Process%20Models/SARS-CoV-2%20Contagion.jpg" width=50% height=50%>
</p>

The *COVID-19 Contagion process* starts when a healthy person enters in contact with the virus (*Start Message Event: Entered in contact with virus*). Then, it is determined in what form they do so (*Task: Define form of contact with virus*). A healthy person can enter in contact with the virus either through an undefined form, or through airborne virus, or through touch.

If the form of contact with the virus is undefined, then the healthy human contracts the virus through an undefined action. (*Task: Contract virus through undefined action*). After that, the process ends with the person being infected (*End Event: Person infected*).

If the form of contact with the virus is through airborne virus, then the healthy human inhales aerosolized virus (*Task: Inhale Aerosolized Virus*). If the form of contact with the virus is through touch, then it can be either by directly touching the virus on another person (direct) or on an object or surface. If the virus is touched in a direct manner, then the healthy human touches their mouth, nose, or eyes with virus-covered hands (*Task: Touch mouth/nose/eyes with virus-covered hands*). If the virus is touched on an object or surface (indirectly), then the healthy human touches the infected-droplet-covered object or surface (*Task: Touch droplet-covered object or surface*). The virus can either still be active or expired on the object or surface. If the virus is still active, then the healthy human touches their mouth, nose or eyes with virus-covered hands (*Task: Touch mouth/nose/eyes with virus-covered hands*). In any of these cases, the process ends with the person being infected (*End Event: Person infected*). If the virus is expired, then the process ends with no infection (*End Event: No infection occurred*).
