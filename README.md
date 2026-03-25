# EXP-6
EXP No. :6 			CHARACTERISTICS M OF LVDT
AIM:To measure output voltage w.r.t the displacement of the core on the LVDT kit and
find the graphical relationship between the two.

APPARATUS: - LVDT kit, Multimeter

THEORY: - LVDT is basically a mutual inductance type transformer with variable coupling between the primary and two secondary coils. It is equivalent to E.Pick off in its operation except the reluctance of magnetic path is mostly due to air path. Uniformly wound over a certain length of transducer and two identical secondary coil systematically wound on either side of the primary coils and away from center. The iron rod is free to move inside the coil in either direction from the null point when primary coil is excitedly AC supply the induced emf of secondary are equal to each other with the core lying in null position. The secondary are connected in series with but in phase opposition so that resultant output voltage is zero.Displacement of core in either direction from the null position results in output voltage as read by an AC rms voltmeter and it is observed that there is a residual voltage at the null position. Due to capacitance coupling between primary and secondary and the characteristics of a linear over a limited  displacement.

DIAGRAM:
CIRCUIT DIAGRAM
PROCEDURE: -
I. Connect the multimeter at the output of kit..
2. Set the range to a maximum value of 10 mm.
3. More the gauge from zero to maximum of 20mm.
4. Value and note the corresponding values of voltages in the multimeter.
5. Plot the graph between displacement and voltages on the graph paper.


OBSERVATION TABLE

PRECAUTION: -
1. The values on the multimeter should be carefully noted.
2. The core should be set to a maximum value of 20mm.
3. To get the good performance from the kit, main room temperature.
4. To check the power supply, it should be 220+!- 10% 50Hz to avoid voltage hazard.


Program:

POSITIVE ANALYSIS 

```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "This smartphone offers outstanding battery life and an intelligent AI camera that captures stunning photos. i want this into negative statement"

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```

NEGATIVE ANALYISIS

```

from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "This smartphone does not offer outstanding battery life and does not have an intelligent AI camera that captures stunning photos."

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
OUTPUT:

<img width="1155" height="326" alt="Screenshot 2026-03-25 102705" src="https://github.com/user-attachments/assets/5f6f255d-4e2a-43e0-af94-f2b2909449ea" />
<img width="1168" height="339" alt="Screenshot 2026-03-25 102201" src="https://github.com/user-attachments/assets/febc77fa-42c4-4902-8f59-257f4bd56742" />


RESULT: -

LVDT was studied well and graph of displacement was linear for a particular range.
