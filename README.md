# Smart-Watch-Analysis
The file contain analysis of smart watches
Data: Here the data is taken from where the Kaggle and assumption is made that the there is no doubt about the integrity of the 
that has been shared.

Problem Statement: The focus is to analyse the data and explore it to provide insights which is critical for the stakholders in decision making

Note: When providing insights using hypothesis test like Annova , spearman, kruskal etc we used 0.05 level of significance as benchmark in our  inferencial analysis.

From above anlysis of smart watches several key points were observed that are mentioned below.


Brands like Apple, Ambrane, fitbit Huawei provides posses very good rating
while rating of zebronics, fire-bolt, is very less.

While comparing battery life brand like Apple, Ambrane, Garmin, Dizo lies 
at the top while Samsung, fitbit, Gizmorea and Hammer perform poor.

Touchscreen and Bluetooth feature impacts the rating of the watch.
People are more likely to rate the watches very good if the touchscreen and Bluetooth
feature is not there in the watch. 

The data of rating is not distribute normally, so preferred non parametric method 
to investigate further about the data 

From Kruskal test it is observed that dial shape impacts rating. Post hoc analysis
using Dunn's test proves that the rectangle over circular, circular over square,
curved over oval, curved over square dial are more likely to rate higher by the end user.
In other words Rectangle and Curved shape effects the rating postivily.

Further investing via Kruskal test about the brand confirms ratings vary with brand. 

Spearman test confirms that rating and battery life is not related linearly
. However, ratings are impacted by the current price positively which conveys higher price is linked to good rating
