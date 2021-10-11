# UFOs

# Overview of Project

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Deliverable 1: Filter UFO sightings on multiple criteria
## Deliverable 2: A written report on the UFO analysis README.md.

### Resources and Before Start Notes:

Data Source: ufo_starterCode.js and index.html
Data Tools: ECMAScript, JavaScript, Jupyter Notebook, Python and MongoDB
Software: ES6+, ECMAScript, MongoDB, Python 3.8.3, Visual Studio Code 1.50.0

# Deliverable 1:

Filter UFO sightings on multiple criteria
Deliverable Requirements:
Using JavaScript and HTML, you’ll modify the code in your index.html file to create more table filters. In addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape, as shown in the following image:
![image](https://user-images.githubusercontent.com/86340630/136723123-eaed974a-ccf1-47c4-94eb-7160cbdd60ee.png)

Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

1. The list element that creates the button is removed, and there are five list elements for filtering in the index.html file.
2. The event listener is modified to detect changes to each filter in the app.js file.
3. The updateFilters() function saves the element, value, and the id of the filter that was changed.
4. The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
5. The webpage filters the table correctly based on user input.

Results with detail analysis:

The list element that creates the button is removed, and there are five list elements for filtering in the index.html file.

![image](https://user-images.githubusercontent.com/86340630/136726471-faa2c16b-0b26-48a4-8030-b3d5d2f9f6f8.png)

The event listener is modified to detect changes to each filter in the app.js file.

![Captura de pantalla (808)](https://user-images.githubusercontent.com/86340630/136727137-0410b789-d0d4-4219-a3a4-7692446923a6.png)

The updateFilters() function saves the element, value, and the id of the filter that was changed.

![Captura de pantalla (815)](https://user-images.githubusercontent.com/86340630/136727873-af4ce99d-060e-47f1-ad97-8f1ae8af66a0.png)

The filterTable() function loops through all of the filters and keeps any data that matches the filter values.

![Captura de pantalla (819)](https://user-images.githubusercontent.com/86340630/136728177-83bae33d-5015-4b5b-a696-6d3493fa5342.png)

The webpage filters the table correctly based on user input.

![Captura de pantalla (823)](https://user-images.githubusercontent.com/86340630/136728466-7b6b5100-86df-466a-85d0-7f7bc4a6671b.png)

# Deliverable 2:

A written report on the UFO analysis
## Deliverable Requirements:
For your written analysis, be sure to use complete and coherent sentences. Your written analysis should contain three sections, which cover the following:

### Overview of Project: Explain the purpose of this analysis.

Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
Results with detail analysis:

Overview of Project: Our UFOs Project has a single mission, and is to enhance our webpage with capability adding filters with multiple factors. D3 functionality makes an instance listener for multiple changes in our search, displaying needed datasets on the result table.

![Captura de pantalla (830)](https://user-images.githubusercontent.com/86340630/136823245-6dc283dd-61f7-4176-86ab-4301a6e60820.png)
![Captura de pantalla (831)](https://user-images.githubusercontent.com/86340630/136825187-f197c013-c12f-49cf-b6b8-ea4c97066072.png)
![image](https://user-images.githubusercontent.com/86340630/136825223-9998feb9-ac85-41e7-b942-240d5eea5871.png)

Results: Let’s describe step by step how someone might use the new webpage by walking through the process of using the search criteria. Using images of your webpage during the filtering process to support your explanation.
Let’s begin reviewing our HTML Filter and Table code.

![Captura de pantalla (835)](https://user-images.githubusercontent.com/86340630/136825573-b8dffcbe-b61c-4267-90ae-fcef081952a6.png)
![Captura de pantalla (836)](https://user-images.githubusercontent.com/86340630/136825692-824ce3e8-37c5-43dd-ab53-c7e44057331d.png)
![Captura de pantalla (837)](https://user-images.githubusercontent.com/86340630/136825795-bc657b95-d2e8-43d5-8da5-80b06bbe2f6e.png)

From our Website (Project Example:) https://www.UFOs.gov

![image](https://user-images.githubusercontent.com/86340630/136825867-b2933fe4-d739-47d6-b8e1-d3e6d305eeb5.png)

Need to visit FILTER SEARCH

![image](https://user-images.githubusercontent.com/86340630/136826027-617dd089-eccd-4993-a0c7-bc42eba2e65a.png)

On filter criteria, you can search by "Shape" only if want, example: triangle

![image](https://user-images.githubusercontent.com/86340630/136826141-518ae559-4459-4551-be1d-0efad4c9378b.png)

And click on "Filter Table" button

![image](https://user-images.githubusercontent.com/86340630/136826207-1b04d69c-b170-4c7e-bad5-5efc3ccd5e93.png)

Automatically your search criteria will appear in our dynamic table resource.

![image](https://user-images.githubusercontent.com/86340630/136826260-78e49bbb-737d-47a2-afc9-584559e62ceb.png)

And, if want to start a new search, just click on "Clear Table" button, and start a new search.

![image](https://user-images.githubusercontent.com/86340630/136826319-f0aafd64-5b64-4f55-a481-7b0998a3e57f.png)

After clear table, you may see our default data

![image](https://user-images.githubusercontent.com/86340630/136826409-d8e08f14-67cf-4d6a-a012-737ed315ec5c.png)

Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
Drawback:

During the project we realized that we needed to publicly expose the information, so it was necessary to use GitHub Pages to bring everything in one place.

Recommendations:

### GitHub Pages - Website Presentation Please use the following GitHub Pages, for more information on how to use IO pages.

### Create a better HTML, CSS, and JavaScript Work interaction that feed UFOs data from most concise and automate workload


















