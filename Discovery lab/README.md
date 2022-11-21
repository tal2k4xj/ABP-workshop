# Discovery Lab:

## Create service, Project & Collection.

[Full information about Projects](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-projects)

[Full information about Collections](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-collections)

1. [Create Discovery Service](https://cloud.ibm.com/catalog/services/watson-discovery) - make sure you select the "plus" plan.

2. Click on "Launch Watson Discovery".

3. Create new project.

4. Give it a name and select "Document Retrival" -> Next.

5. Select "Upload Data" -> Next.

6. Give it a name and select "Hebrew" -> Next.

7. Upload the [samsung tv user guide](https://github.com/tal2k4xj/ABP-workshop/blob/main/Discovery%20lab/samsung%20tv%20user%20guide.pdf) -> Finish.

## Smart Document Understanding (SDU)

[Full information about SDU](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-configuring-fields)

1. Go to "Manage collections" and select the collection you created.

2. Click in the "Identify fields" tab.

3. Choose "User-trained models"

4. Click Submit, and then click Apply changes and reprocess.

5. Start label your document, when you done click "Apply changes and reprocess".

6. Go to "Manage fields" tab, uncheck the followings: answer, author, footer, header, image, question, table_of_contents.

7. Select "Split the document +" and select the title field.

8. Select the currect timezone, click Apply changes and reprocess.

## Entity extraction

### Dictionaries

[Full information about document Dictionaries](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-domain-dictionary)

1. From the "Teach domain concepts" section of the "Improvement tools panel", choose "Dictionaries".

2. Click New, Choose the language. A dictionary can contain terms in only one language.

3. Add a term and synonyms or upload [samsung tv dictionary](https://raw.githubusercontent.com/tal2k4xj/ABP-workshop/main/Discovery%20lab/samsung%20dictionary.csv), when you finish "Save dictionary".

### Entity extractor

[Full information about document Entity extractor](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-entity-extractor)

1. Click Improve and customize from the navigation panel.

2. From the Improvement tools panel, expand Teach domain concepts, and then click Extract entities.

3. Click New., Add an extractor name.

4. Choose a collection with documents that are representative of your domain data.

5. Choose fields from the document to show in the document view where you will label documents from the collection.

## Classifiers

[Full information about text Classifiers](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-domain-classifier)

[Full information about document Classifiers](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-cm-doc-classifier)

1. Go to "Improve and customize", from the right menu select "Teach domain concepts" and select "Classifiers"

2. Click in "Upload", give it a name and select "Hebrew", upload the [samsung classifier.csv](https://raw.githubusercontent.com/tal2k4xj/ABP-workshop/main/Discovery%20lab/samsung%20classifier.csv)

3. Select the relevant fields.

## Regular expressions

1. From the Teach domain concepts section of the Improvement tools panel, choose Regular expression.

2. Click Upload.

3. Add the regular expression.

4. Click Create.

## Query

[Full information about Query](https://cloud.ibm.com/docs/discovery-data?topic=discovery-data-query-concepts)
