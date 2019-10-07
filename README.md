# Assignment 2 - Creating Charts

### Learning Goal
Train yourself in creating a visualization appropriate for a specific dataset.

### Dataset - Atlanta Crime dataset

This data details the crimes committed in the city/greater metropolitan area of Atlanta from the year 2009 to 2018.

The attributes of this dataset are: 

- Report Number
- Beat (In police terminology, a beat is the territory and time that a police officer patrols.)
- Report Date
- Occur Date and Time
- Apartment Number
- Location (Address)
- Shift Occurrence ( a value that can be [Morning, Day, Evening])
- UCR (Uniform Crime Reports) a code that represents the type of crime.
- Neighborhood
- NPU (Neighborhood planning unit) 25 values



### Instructions

#### Step 1

Make sure you have a clear understanding of what each attribute means and what values it contains (ask questions to the instructor if you have doubts).

#### Step 2

Create data visualization sketches to investigate the following questions. For each sketch describe in words what are the marks and channels that are used.

1. What are the most dangerous neighborhoods?


If number of neighborhoods are less than 10:




![chart1](/Q1a.png)

If number of neighborhoods are less than 10:

Attributes and theeir marks and channels are:

1.Neighborhood Name

  Type:Categorical
  
  Mark: Line
  
  Channel: Position(Vertical)
  

2.Different types of crime (Derived from UCR):

  Type:Categorical
  
  Mark: Area
  
  Channel: Color(Saturation)
   

3.Total Number of crimes in each neighborhood(Derived attribute):

  Type:Quantitative
  
  Mark: Area
  
  Channel:Position(Horizontal)+ Size (Area)


----------------------------------------------------------------------------
If number of neighborhoods is a high value greater than 10 :


![chart1](/Q1b.png)


If number of neighborhoods are greater than 10:

1.Neighborhood

  Type:Categorical
  
  Mark: Area
  
  Channel: Shape


2.Crime rate in each neighborhood:

  Type:Ordinal
  
  Mark: Area
  
  Channel: color


---------------------------------------------------------------------------------------------------------------------------


2. What are the most dangerous times of a day?




![chart1](/Q2.png)

Attributes and their marks and channels are:

1.Time interval:
  
  Type:Ordinal

  Mark: Line

  Channel: Position(Vertical)

2.Number of Crimes in each interval(Derived attribute):

  Type:Quantitative

  Mark: Area

  Channel: Size(Length)


3. Are crimes increasing or decreasing since 2008?


![chart1](/Q3.png)

Attributes and theeir marks and channels are:

1.Year

  Type:Ordinal

  Mark: Point

  Channel: Position(Horizontal)

2.Number of Crimes in each year(Derived attribute):

  Type:Quantitative

  Mark: Point

  Channel: Position(Vertical)





#### Step 3

Now suppose to have the following additional data.

- Immigration status (this indicates the immigration status of the person reporting the crime can be either "Citizen" or "Immigrant")
- Amount (this indicates the amount of stolen/damaged goods)


Create data visualization sketches to investigate the following questions. For each sketch describe in words what are the marks and channels that are used.

4. Are immigrants more likely to get involved as a victim of a crime?


![chart1](/Q4.png)





Attributes and their marks and channels are:

1.Immigration Status

  Type:Categorical
  
  Mark: Line

  Channel: Position(Horizontal)


2.Number of people:

  Type:Quantitative

  Mark: point

  Channel: Position(Vertical)



3.Number of Victims for each Immigration Status : (Derived attribute)

  Type:Quantitative

  Mark: point

  Channel: Size(Area) + color 




4.Number of Non Victims for each Immigration Status:(Derived attribute)

  Type:Quantitative

  Mark: point

  Channel: Size(Area) + color 
  
  

5. What is the cost for the society (people of Atlanta) for the crimes that happened in 2018?

![chart1](/Q5.png)


Attributes and their marks and channels are:


1.Cost to Society( Derived from Amount attribute):

Type:Quantitative

Mark: Point

Channel: Position (Vertical) + Size



2.Year(derived from Occur Date attribute): 

Type:Categorical

Mark:Line

Channel: Position (Horizontal)




3.Type of Crime:

Type:Categorical

Mark: Area

Channel: color 



#### Bonus

Define your own question and design a visualization for answering it.

6: How is the trend of the cost per year for the people of Atlanta because of these crimes?

![chart1](/Q6a.png)


Attributes and their marks and channels are:

1.Type:Quantitative

Mark: Point

Channel: Position (Vertical) 



2.Year: 

Type:Categorical

Mark:Point

Channel: Position (Horizontal)


### Submission

Modify this README file by adding sketches of the visualization designed. Pair each image with a description of the marks and channels used.

... update file from here
