# School_District_Analysis

Overview: In this analysis we do a couple things. The first is we remove the grades of the Freshman (9th grad) class of Thomas High School pending investigation into academic dishonesty. The second is to look at the overall grades based on math and reading for all schools, which schools performed the best, which performed the worst, if and how money spent per student affected scores, as well as grades per school size and type. 

**Results**

**How is the district summary affected?**

Here is a comparison between the initial district summary 
![image](https://user-images.githubusercontent.com/94264746/162354604-01993ae3-ebde-4bef-9707-cd2e70ac4992.png)

And the second one:
![image](https://user-images.githubusercontent.com/94264746/162354655-a9764f50-6377-4f2e-9162-0216f8670b0d.png)

As you can see, overall the grades remain largely the same, it doesn't appear that replacing the Freshman class of Thomas High School's grades has affected much.

**How is the school summary affected?**

Here is the summary from the initial run: ![image](https://user-images.githubusercontent.com/94264746/162355550-6ed4f129-d037-4850-bc3f-fe0d89c2b1de.png)

And the subsequent:
![image](https://user-images.githubusercontent.com/94264746/162355589-5dd40495-4d80-4d68-95db-17a5251285d9.png)
As you can see the scores remain largely unchanged, except for Thomas High School's.

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

As per the above images, Thomas HS took a massive hit to performance with the removal of the Freshman class' grades, going from almost 91% to 65%. Further investigation is definitely needed to see what caused such a drastic drop.

**How does replacing the ninth-grade scores affect the following:**

**Math and reading scores by grade**

Here are the math scores in the initial summary: 

![image](https://user-images.githubusercontent.com/94264746/162356979-fd37847b-893f-4668-b4eb-a842d114767d.png)

And in the second: 

![image](https://user-images.githubusercontent.com/94264746/162357043-2ccffd5a-6927-4ff5-939a-a84d079ef6b1.png)

It looks like removing THS 9th grade does not change much.

As for reading, here is the initial summary:

![image](https://user-images.githubusercontent.com/94264746/162357414-5c00816e-4b5a-4ed5-ace3-4dd52bdae27b.png)


And the second:

![image](https://user-images.githubusercontent.com/94264746/162357505-eb27be66-99cb-4f76-a466-b574cdc3f5e1.png)

Again, it appears that removing the grades of the THS Freshman doesn't affect the other data at all.

**Scores by school spending**

Analysis 1:

![image](https://user-images.githubusercontent.com/94264746/162357829-284519f2-7405-40e3-b0e5-6c57de85def5.png)

Analysis 2:

![image](https://user-images.githubusercontent.com/94264746/162357895-c8d93ef9-446d-4336-affb-b940c6bfe0dc.png)

Here we see a marked difference within the $630-645 range, with a drop from 63 to 56 in overall passing. However the rest of the scores in that bin don't seem to be that much affected.

**Scores by school size**

Analysis 1:

![image](https://user-images.githubusercontent.com/94264746/162358590-740355d6-d9b4-4663-ba2e-8293fc949504.png)


Analysis 2:

![image](https://user-images.githubusercontent.com/94264746/162358654-5314ca31-7fde-4b3e-9b75-b2b6230428f5.png)

Here we can see that the medium sized schools took a fairly decent hit to overall passing rate, going from 91 to 85. Reading for medium sized schools also experienced a slight dip, going from 97 to 95, though the other grades seem to be unchanged.

**Scores by school type**

Analysis 1:

![image](https://user-images.githubusercontent.com/94264746/162359271-10d19ef6-6cb6-4963-8631-921e091cf03a.png)

Analysis 2:

![image](https://user-images.githubusercontent.com/94264746/162359304-ccb23e98-8ba5-4ffd-a618-5eb7f0e0259d.png)

Once again we see a drop in Charter schools overall passing score, going from 90 to 87. Reading for Charter schools also went down from 97 to 96.

**Summary:** 
When removing the scores of the ninth grade of Thomas High School, the biggest change to the overall scores is that Thomas HS goes from a 90% passing rate to just 65%, a shocking drop. That removing the scores of that particular class has little affect on the other schools themselves is very suspicious. Medium sized schools also took a big drop, as did Charter schools, both of which Thomas High School is classed as. In conclusion, it's probably safe to assume that the original scores of the Freshman class at Thomas High School are not accurate and should be examined more closely.
