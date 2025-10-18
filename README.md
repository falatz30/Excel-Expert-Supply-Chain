# Excel-Expert-Supply-Chain
These files are designed to demonstrate my proficiency in Excel, with a focus on sophistication, automation, and readability. Each workbook is modeled after real-world projects, with datasets replicated and randomized directly in Excel to protect sensitive information. The datasets have been simplified to include only the most relevant columns, highlighting the core analytical and reporting processes.

Walkthroughs:

Capacity by Plant:
   &nbsp;&nbsp;
   &nbsp;&nbsp;
   On the task worksheet cell A5 can be manipulated to one of the following values {Press, Melt, Cut} and the chart updates.

Constraining Model:
    &nbsp;&nbsp;
    &nbsp;&nbsp;
    Imainge that you would like to keep the median of Col C the same, however the sum of Col B needed to decrease to the target highlighted in column G. The formula in column D2 identifies which values could be taken to constrain A, such that the median of                      col B would be the same. This concept is proven in I8. A new dataset can be shown if K2 is set to 'Yes' then col B & C are copied to col V & W and turn the shuffle back to 'off'. Furthermore the target values can changed.

Minimum Inventory Model:
    &nbsp;&nbsp;
    &nbsp;&nbsp;
    Sheets 'OH' {On-Hand},'Supply','Demand' are the incoming datasheets. In practice these were all SQL connections. Sheet 'Min Inv' has two toggles that can be adjusted for an item {'a','b','c'} and the length of your demand fence. The dynamic formula and                      chart update according to the inputs. Beside the chart, the length of the shortages are shown, i.e. on item 'b', and the excessive production orders that could be cancelled, i.e. on item 'c'.
