Project Introduction and Objective
After two weeks of intensive learning at LuxDev HQ, where I was introduced to different concepts, tools, and practical approaches in data analytics, I wanted to take what I had learned beyond the classroom and put it into practice.
I realized that learning data analytics is not only about understanding formulas, functions, or visualization tools. It is also about being able to take a raw dataset, identify a problem, ask the right questions, analyze the information, and communicate findings in a way that can support decision-making.
With this in mind, I wanted to work on a project that would challenge me to apply the skills I had gained during those two weeks. I decided to use a Jumia e-commerce product dataset because e-commerce provides an interesting environment for exploring customer behavior, product performance, pricing, discounts, ratings, and reviews.
At first, the project seemed straightforward: analyze the dataset and create a dashboard. However, as I started working with the data, I realized that the process involved much more than creating charts. I had to first understand the structure of the dataset, check its quality, clean it, create additional fields, analyze relationships, and then determine how best to present the results.

My main objective was therefore to go through a complete data analytics workflow:
Raw Data → Data Quality Audit → Cleaning → Data Preparation → Analysis → Visualization → Dashboard → Insights → Recommendations

The central question I wanted to answer was:
“What can Jumia product data tell us about pricing, discounts, customer engagement, and product performance?”

To answer this question, I focused on several business questions:

1.Does a higher discount percentage result in more customer reviews?
2.Is there a relationship between product ratings and the number of customer reviews?
3.Are more expensive products rated higher than cheaper products?
4.Which products have the highest ratings?
5.Which products have the lowest ratings?
6.Which products have the highest discounts?
7.Which products have the highest number of reviews?
8.Which products have high discounts but low ratings?
9.Which products demonstrate strong customer engagement?
10.Which products may need better pricing or marketing strategies?

For me, this project became more than an Excel assignment. It became an opportunity to understand how the different skills I had been learning could work together to turn raw data into meaningful insights and business recommendations.

Dataset and Business Questions
The dataset I worked with contained information about products listed on Jumia. Some of the important fields included information relating to:

Product name
Original price
Sale price
Discount
Rating
Number of customer reviews
Product categories and other product attributes_
I chose these variables because they provide different perspectives on product performance.
For example, price and discount can help understand pricing strategies, while ratings and reviews can provide an indication of customer engagement and satisfaction.

Instead of simply asking, “Which products are selling well?”, I wanted to explore several dimensions of performance.

Pricing
I wanted to understand whether price had any noticeable relationship with product ratings.

Discounts
I wanted to investigate whether heavily discounted products necessarily attracted more customer engagement.

Ratings
Ratings could help identify products that appeared to perform well in terms of customer satisfaction.

Customer Reviews
The number of reviews could provide an indication of customer engagement, although I recognized that reviews are not the same as actual sales.
This led me to develop a set of questions that would guide my analysis rather than simply exploring the dataset without a clear purpose.

Initial Data-Quality Audit
One of the biggest lessons I learned from this project was that data analysis should not begin with visualization.
Before creating PivotTables or charts, I first needed to understand whether the data was suitable for analysis.
I therefore carried out an initial data-quality audit.

I looked for issues such as:

_Missing values
Duplicate records
Incorrect data types
Numbers stored as text
Inconsistent formatting
Unusual values
Blank fields
Incorrect or inconsistent entries
This stage helped me understand that the quality of my analysis would depend heavily on the quality of the data I was working with.
For example, if prices were stored inconsistently or ratings were treated as text rather than numbers, calculations and visualizations could produce misleading results.
The audit therefore became an important checkpoint before moving to the cleaning stage.

Cleaning and Preparation Decisions
After identifying potential data-quality issues, I started cleaning and preparing the dataset.
My cleaning process included checking for duplicate records and reviewing missing or inconsistent values.
I also checked that numerical fields were properly formatted so that Excel could perform calculations correctly.

Some of the main steps included:

Removing or reviewing duplicates
Duplicate records can affect counts, averages, and rankings. I therefore checked the dataset for duplicate entries and reviewed them before deciding how they should be handled. I found a total of three duplicates.

Correcting data formats
Fields such as price, rating, discount, and number of reviews needed to be treated as numerical values.

Standardizing information
I checked for inconsistencies in formatting and naming so that PivotTables and filters would work correctly.

Handling missing values
Rather than automatically deleting every row containing a blank value, I considered how each missing value could affect the specific analysis I was performing.
This was an important lesson for me because cleaning is not simply about deleting information. It involves making decisions about what should be retained, changed, or excluded and why.

Excel Formulas and Enrichment Fields
Once the dataset was cleaned, I created additional fields to make the analysis more useful.
One of the important calculated fields was the Discount Percentage.
Instead of relying only on the discount value provided in the dataset, I calculated the percentage based on the original and sale prices.
The formula I used was:
=(Original Price-Sale Price)/Original Price
I then formatted the result as a percentage.
This allowed me to compare discounts more consistently across products.
I also created categories that made it easier to group products.
For example, products could be classified into **price categories **such as:

Affordable
Moderate
Expensive I also considered rating categories such as:
High Rating
Average Rating
Low Rating
These additional fields helped transform the raw dataset into information that was easier to analyze.
This was one of the areas where I began to appreciate the importance of data enrichment. Instead of only working with the fields that already existed, I could create new information from the existing data to answer more meaningful questions.

PivotTable and Analysis Workflow
After cleaning and enriching the dataset, I moved into the analysis stage.
This is where PivotTables became particularly useful.
Rather than manually calculating every result, I used PivotTables to summarize the information and identify patterns.

Some of the analyses I performed included:
1.Top 10 products by discount
I identified products with the highest discount percentages.
This helped me investigate which products were being promoted most aggressively.
2.Top 10 products by number of reviews
I ranked products according to the number of customer reviews.
This provided an indication of which products had attracted significant customer engagement.
3.Top 10 highest-rated products
I analyzed the products with the highest ratings to identify potential strong performers.
4.Top 5 highest-rated products
I created a smaller ranking to highlight the strongest-rated products.
5.Top 5 lowest-rated products
I also looked at the lowest-rated products because poor ratings can highlight areas that may require attention.
6.High discount and low rating
One of the most interesting areas of analysis was identifying products that had high discounts but relatively low ratings.
These products stood out because a large discount does not necessarily solve problems related to customer satisfaction.
7.Strong customer engagement
I also looked for products that had a high number of reviews and appeared to have strong customer engagement.
8.Exploring Relationships Between Variables
Beyond rankings, I wanted to understand the relationships between different variables.
This was important because ranking products only tells me what is happening. Relationship analysis helps me start thinking about why certain patterns may exist.
9.Discount Percentage vs. Customer Reviews
One of the questions I investigated was:
I used this relationship to explore whether products with larger discounts also tended to have higher customer engagement.
The analysis helped me understand that a discount alone does not necessarily guarantee high customer engagement.

10.Rating vs. Customer Reviews
I also investigated;
Is there a relationship between product ratings and the number of customer reviews?

This allowed me to compare customer engagement with customer satisfaction.
A product can have many reviews while still having an average rating, which can be an important business signal.
11.Price vs. Rating

Another question was:
Are more expensive products rated higher than cheaper products?

This helped me examine whether higher product prices were associated with better customer ratings.
The analysis suggested that price alone should not be assumed to determine customer satisfaction.

Dashboard Design and Slicer Connections
After completing the analysis, I wanted to bring everything together into an interactive dashboard.
My goal was not simply to place as many charts as possible on one page. I wanted the dashboard to tell a story.
I therefore organized the dashboard around the main questions I had explored.

Key Performance Indicators
I included important summary figures such as:

Total Products
Average Price
Average Discount
Average Rating
Total Reviews
These KPIs provide a quick overview before the user moves into the detailed analysis.

Visualizations
I included charts for areas such as:

Top 10 products by number of reviews
Top 10 highest-rated products
Top 10 products by discount
Discount vs. rating -** Discount vs. number of reviews**
Product performance comparisons
I used different types of charts depending on the question being answered.
For example, a scatter plot was useful when I wanted to investigate relationships between two numerical variables.
The scatter plot for discount percentage versus rating helped me identify products that combined relatively high discounts with lower ratings.

Connecting the Slicers
One of the features I wanted to include was interactivity through slicers.
Slicers allow users to filter the dashboard without manually changing the underlying PivotTables.
I connected the relevant slicers to the PivotTables and Pivot Charts so that filtering one part of the dashboard could update the relevant visualizations.
This made the dashboard more interactive and easier to explore.
It also taught me an important lesson:

*Dashboard design is not only about appearance; it is about usability and the user's ability to interact with the information.
*

Key Findings
After completing the analysis, several observations stood out to me.

High discounts do not automatically mean high customer engagement One of the interesting observations was that products with high discounts were not necessarily the products with the highest number of reviews. This suggests that discounting can attract attention, but other factors may influence whether customers engage with a product.
These factors could include:

Product quality
Brand reputation
Price after discount
Customer experience
Product demand
Seller reputation
High customer engagement does not always mean high satisfaction
Some products may have a large number of reviews while maintaining only average ratings.
This is an important finding because a high number of reviews can initially look positive.
However, when the rating is considered alongside the number of reviews, the story becomes more detailed.
A product with many reviews and an average rating may be receiving significant attention but still have customer satisfaction issues.

Higher prices do not guarantee higher ratings
Another important observation was that expensive products should not automatically be assumed to receive better ratings.
Price and customer satisfaction are not necessarily directly related.
This means businesses should consider other factors when evaluating product performance rather than assuming that premium-priced products will naturally have better customer experiences.

High-discount and low-rated products deserve attention
Products that combine significant discounts with low ratings stood out as an important group.
A business might be investing heavily in discounts to encourage purchases, but if customers are still leaving poor ratings, the underlying issue may not be price.

The business may need to investigate:

Product quality
Product description accuracy
Customer expectations
Seller performance
Delivery experience
Product defects
Highly rated products represent potential opportunities Products with strong ratings can potentially be used as examples of successful product performance.
These products may provide opportunities for:

Increased promotion
Cross-selling
Featured placement
Marketing campaigns
Customer testimonials However, I would still want to combine ratings with other information before making a final business decision.
Business Recommendations
Based on the analysis, I developed several recommendations.

Use discounts strategically Businesses should avoid assuming that larger discounts automatically produce better results. Instead, discounts should be evaluated alongside:
Reviews
Ratings
Price
Product category
Customer engagement
This can help determine whether a discount is actually contributing to better product performance.

Investigate low-rated products
Products with consistently low ratings should be investigated.
Rather than simply increasing their discounts, businesses should try to understand the reason behind the poor ratings.
This could involve reviewing customer feedback and identifying recurring complaints.

Turn customer reviews into business intelligence
Customer reviews contain valuable information.
Businesses can use review patterns to identify:

Product quality problems

Customer complaints

Common expectations

Service issues

Opportunities for improvement
Reviews should therefore be treated as more than just a number.

Promote strong-performing products
Products that combine strong ratings with high customer engagement may deserve greater visibility.
Businesses could consider featuring these products in marketing campaigns or promotional activities.

Focus on customer experience
The analysis reinforced the idea that price and discounts are only part of the customer experience.
Businesses should also consider:

Product quality

Accurate product descriptions

Seller reliability

Delivery experience

After-sales service
Improving these areas could contribute to stronger customer satisfaction.

Segment products before making decisions
Not every product should be managed using the same strategy.
Products could be segmented into groups such as:

High rating + high engagement

High rating + low engagement

Low rating + high engagement

Low rating + high discount

Low rating + low engagement
Each group may require a different business strategy.

Limitations and Lessons Learned
Like any analysis, this project had limitations.

The dataset represented a particular collection of Jumia product information and may not represent the entire Jumia marketplace.
Another important limitation is that customer reviews are not the same as actual sales.
A product with many reviews may have strong engagement, but without actual transaction data, I cannot confidently say that it generated the highest sales.
There were also other factors that were not available in the dataset, such as:

Seller reputation
Delivery performance
Stock availability
Advertising expenditure
Customer demographics
Seasonal effects
Actual sales volume
Return rates
Therefore, the relationships I observed should not automatically be interpreted as cause-and-effect relationships.

For example, if a highly discounted product has many reviews, I cannot conclude that the discount alone caused the high number of reviews.

What I Learned From the Project
For me, one of the most valuable parts of this project was the learning process itself.
After two weeks of intense learning at LuxDev HQ, I wanted to challenge myself to move from learning concepts to applying them.

This project helped me understand several important areas.

1.Data quality comes first
I learned that creating a beautiful dashboard means very little if the underlying data is unreliable.
The quality of the analysis starts with the quality of the data.

2.Cleaning is an analytical skill
I initially thought of cleaning as simply preparing data for analysis.
I now understand that cleaning also involves making decisions about missing values, duplicates, formats, and inconsistencies.

3.Excel can support an entire analytical workflow
Through this project, I was able to use Excel for:

Data cleaning
Data transformation
Calculated fields
Formulas
PivotTables
Pivot Charts
Filtering
Slicers
Dashboard development
This helped me see Excel not just as a spreadsheet tool, but as a practical tool for analyzing and communicating data.

4.Asking the right questions matters
I also learned that analysis becomes much more meaningful when it starts with clear questions.
Instead of simply asking:
“What does the data show?”

I learned to ask more specific questions such as:
“Does a higher discount correspond with higher customer engagement?”

That shift helped me approach the dataset more critically.

5.A dashboard should tell a story
I learned that visualization is not simply about creating charts.
Each chart should have a purpose.
The dashboard should help someone quickly understand:
What is happening? → Why might it matter? → What should we investigate or do next?

6. Insights should lead to action
The final stage of analysis should not stop at saying what the numbers show.
A good analysis should help decision-makers understand what they could do with that information.
That is why I included recommendations alongside my findings.

Project Resources
I documented the project and supporting materials as part of my learning and portfolio development on my Github repository.

Conclusion
This Jumia product analysis project was an important part of my data analytics learning journey.
After two weeks of intense learning at LuxDev HQ, I wanted to challenge myself to take the knowledge I had gained and apply it to a real dataset.
What started as an idea to create an Excel dashboard became a much broader learning experience.
I had to learn how to approach raw data, audit it's quality, clean and prepare it, create calculated fields, analyze relationships, build PivotTables, design visualizations, connect slicers, identify insights, and finally translate those insights into business recommendations.
The project also taught me that data analytics is not simply about knowing how to use Excel.

It is about asking the right questions, understanding the data, finding meaningful patterns, communicating those patterns clearly, and thinking about how the findings can support better decisions.
Most importantly, this project gave me an opportunity to move from theory to practice.It showed me that I can take a dataset that initially looks like rows and columns of information and gradually turn it into a story that people can understand.
For me, this is only one step in my data analytics journey, but it is an important one.

From raw data to insights. From insights to decisions. And from learning to practical application
