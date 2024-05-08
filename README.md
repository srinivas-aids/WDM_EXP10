### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 07-05-2024
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:

![328104422-087fd1a3-9dd8-4e3f-8b09-3bb3a57d7685](https://github.com/AdhithiyanK/WDM_EXP10/assets/121029258/a0e0fa94-78b7-4610-8301-dec25edad879)

![328104469-3e7416e1-5982-4d3a-825b-da32f71b03e7](https://github.com/AdhithiyanK/WDM_EXP10/assets/121029258/62ef8656-4ada-4b63-b750-ccfbabfd9fe8)

![328104491-31faacdf-a75c-493d-88c1-32daf556402f](https://github.com/AdhithiyanK/WDM_EXP10/assets/121029258/cdb606d7-01de-418d-9863-aa09fdfd8fbd)


### Result:

Thus sentimental analysis for twitter data is executed successfully using rapidminer.Thus sentimental analysis for twitter data is executed successfully using rapidminer.
