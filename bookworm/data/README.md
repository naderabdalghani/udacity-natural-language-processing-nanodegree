data
1. Create and configure Discovery service

    Prepare an environment: Notebook connects to a Discovery service instance and creates/fetches an environment.
    Test configuration: The service processes a small sample text and returns enriched output.
    Analyze test output: All inline questions are answered correctly based on the output, and a word-cloud of keywords is shown.

2. Ingest documents

    Prepare a document collection: A collection is created and documents are added to it, one document per paragraph of text.
    Test query: A simple query is made against the collection, and relevant results are returned. Inline questions are answered correctly.

3. Parse natural language questions

    Add intents: At least 3 intents are added to the Conversation service, each with at least 5 example utterances. Inline questions are answered adequately.

    Add entities: At least 3 entities are added to the Conversation service, each with at least 1 example entity. Inline questions are answered adequately.

    Design dialog flow: An appropriate dialog flow has been designed using the Conversation service workspace tool, with at least 3 nodes. Inline questions are answered adequately.

    Test dialog: A simple 1-question dialog is demonstrated in the notebook, showing what node was triggered.

4. Query document collection to fetch answers

    Process sample question: A sample question is run through the Conversation service. The intent and entities identified are extracted, and optionally the dialog node that was triggered.

    Query the collection: A query is designed based on the information extracted in the previous step, and run against the Discovery service collection.

    Process returned results: Results obtained from the Discovery service are processed to provide a specific response to the natural language question that was asked.

5. Reflections

    Reflections: Inline question adequately answered, including strengths and weaknesses of an API-based solution like this.
