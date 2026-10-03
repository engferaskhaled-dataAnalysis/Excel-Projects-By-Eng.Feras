	Cleaning data : 
	A- (Remove all row Null)
	B- Change kind of data to Short date.
  ## Dataset used
  - <a href="https://github.com/engferaskhaled-dataAnalysis/Excel-Projects-By-Eng.Feras/blob/main/Pivot%20Tables%20Task%20(try%20by%20feras).xlsx">DataSet view</a>
  
	C- Calculate inside table (data Source):
	Revenue : Price * Order Quantity 
	Cost : Unit cost * Order Quantity
	Profit : Revenue - Cost
	C- Choose table then choose one cell inside table then Insert Pivot Table.
	Revenue by Top five city in each Country:
	Choose country first in Rows
	Choose city second in Rows
	Choose revenue in values
	Choose top city number 5 in highest sales.
	Relation between Cost and Revenue by subcategory
	What the relation between Cost and Revenue?
	When the cost increase does the Revenue increase.
	When the cost decrease does the Revenue increase.
	Choose Revenue & cost in value pivot table
	Choose subcategory in Rows pivot table.
	Revenue% for each Channel in each region:
	Choose Region in Rows pivot table
	Choose Channel in Rows Pivot Table.
	Choose profit then choose shows value as Grand %
	For each year calculate var month over month revenue%:
	Choose Year & Month in Rows
	Choose profit  in Values
	Choose again Profit in Values then choose cell of number then click right shows values as % Difference from choose month then previous .
	For each subcategory If cost% <25% give discount 7% on revenue but if cost <35% give discount 5%:
	Choose subcategory in Rows pivot table
	Choose Cost%  & Revenue in Values
	Choose cell inside pivot table choose calculated field
	Write : Discount%
	Formula : =IF('Cost%'<0.45,Revenue*0.07,IF('Cost%'< 0.5,Revenue*0.05,0))
Quick Check: Formula Reference
Measure	Formula	Calculated Field Expression
Cost % (Cost of Goods Sold Ratio)	"Cost" /"Revenue" 	= Cost / Revenue
Profit % (Profit Margin)	"Profit" /"Revenue" 	= Profit / Revenue
