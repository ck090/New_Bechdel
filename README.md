# New_Bechdel
Program to set up the alternative to the Bechdel test

Dataset derived from the Cornell Movie-Dialogue Corpus


## Steps to consider in the model

- [ ] Explore the data.
- [ ] Creating and Finding out features.
- [ ] Gathering data from the Crew as well and linking it with the existing dataset.
- [ ] Number of dialogues a Female has spoken in the movie - Percentage.
- [ ] Dialgoues in the form of f-f, f-m, m-f should be considered.
- [ ] Identifying Parts of Speech (POS) tags per movie, and understanding how many f-f, f-m and m-f utterances can be found.
- [ ] Identifying the sentiments of each utternaces in the movie by understanding what are the sentiments like for f-f, f-m and m-f characters.
- [ ] Linking the overall sentiments of the movie with the genres of the movie.
- [ ] Identifying how all these above parameters affect the ROI of the particular movie.
- [ ] We define ROI as the ratio of the 'Budget Of The Movie' to its 'Revenue'
- [ ] We obtain principal components from the various parameters we obtain from the above steps, in order to depict the variability in the independent variables(features).
- [ ] We then compute the participation of each of the features in the first few components of the principal components, and use that to establish a score which would be as follows
<br>Score = b1\*P1 + b2\*P2 + b3\*P3 ..
<br> Where b1, b2 .. are the participation of feature1, feature2 ... respectively in the first few principal components.
- [ ] We would regress our principal components obtained from the features above to obtain their regression coefficients, and how the ROI(dependent variable) is related to them.
- [ ] Finally find out the existing Bechdel score and prove how this score is better at identifying the gender equality or gender diversity in that particular movie.
