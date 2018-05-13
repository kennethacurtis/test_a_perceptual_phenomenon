# Analyzing the Stroop Effect

The <a href='https://en.wikipedia.org/wiki/Stroop_effect'>**Stroop Effect**</a> is a test that demonstrates the difference in reaction times of a task. In the Stroop task, you are presented with a list of words. Each word displayed has a color. The task of the participant is to say out loud the color of the ink in which the words is printed. The two conditions of this task are a congruent words condition, and an incongruent words condition. The congruent words condition has the color matching the word of that color (<a href='https://en.wikipedia.org/wiki/Stroop_effect'>see wiki for example</a>). The incongruent words are displayed with the colors not matching the word, (<a href='https://en.wikipedia.org/wiki/Stroop_effect'>see wiki for example</a>). Each case is measured by the time it takes to read the word group. The groups are then compared.

#### Interference

The Stroop Effect experiment demonstrates Interference. Interference occurs when you look at one of the words, you see both its color and its meaning. These two different bits of information begin to confuse the brain, which then causes a conflict, forcing you to make a choice. Our experiences and stored memories has taught us that word meaning is more important than the color a word is written in. Interference occurs when you try to pay attention only to the color. The interference that happens suggests that you are not always in control of what you can pay attention to. This interference is called the ‘Stroop Effect’.

To explain this occurrence of interference, J. Ridley Stroop developed these two theories:

#### Speed of Processing Theory:
The Speed of Processing Theory states that people can read words much faster than they can name colors.

#### Selective Attention Theory:
In this theory, interference occurs when naming the actual color of the words requires much more attention than reading the test presented to you.


# Conclusion

Based on the statistical analysis, we can reject the null hypothesis. This outcome was not surprising to me because early on we had strong evidence that the two groups were not the same after directly subtracting the two groups in the original dataset. After using bootstrapping to get the distribution of the means, I created a 95% confidence interval (A Type-I Error rate of .05). The observed mean fell within this confidence interval which provided more evidence that the groups are not the same.

Furthermore, this investigation supports the **Selective Attention Theory** in which it takes longer for the brain to process the color than just reading the word displayed. The main cause of the effects observed is the phenomenon called **interference**. As discussed above, this occurs when you try to pay attention only to the color of the word. Our brains our trained to first observe the word written rather than the color of the word.


# Sources

* <a href='https://www.verywellmind.com/what-is-the-stroop-effect-2795832'>The Stroop Effect: Naming the Color but Not the Word</a>
* <a href='https://en.wikipedia.org/wiki/Stroop_effect'>Wikipedia: Stroop Effect</a>
* <a href='http://www2.psychology.uiowa.edu/faculty/mordkoff/GradStats/part%201/I.07%20normal.pdf'>The Assumption(s) of Normality</a>
