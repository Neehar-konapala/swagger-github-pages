HachiAI API Documentation
=========================

Live Demo
---------

Visit your hosted Swagger UI documentation at:https://{your-github-username}.github.io/{your-repository-name}/

Using the Documentation to Test APIs
------------------------------------

With Swagger UI, you can test your APIs directly from the web browser — no Postman or command line is needed. Here’s how:

1\. Get Your API Key
--------------------

You must have a valid X-API-KEY. If you do not have one, contact your administrator or support team.

2\. Authorize Yourself
----------------------

*   On your Swagger page, click the green **Authorize** button at the top or next to any endpoint.
    
*   In the dialog box, enter your API key (just the key, NOT "X-API-KEY: ...").
    
*   Click **Authorize**, then **Close**. Now all your API calls from the UI will use this key automatically.
    

3\. Explore Endpoints

Review the available endpoints in the documentation. For this API, you’ll see:

MethodEndpointWhat it doesPOST/v1/classifyAnalyze and classify invoice pagesGET/v1/trace\_id/{trace\_id}Check processing status by trace IDPOST/v1/llm/qna/conversations/asyncLLM QnA Playground (Async)POST/v1/extract/asyncDocument Extraction (Async)POST/v1/extractDocument Extraction (Sync)POST/v1/llm/qna/asyncLLM QnA (Async)

4\. Make a Test API Request
---------------------------

Here’s how to send any request through Swagger UI:

**A. Select an Endpoint**Scroll through the list and click on an endpoint you want to test (e.g., /v1/classify).

**B. Understand the Parameters**The UI shows required and optional parameters for each request, along with helpful documentation and input types.

**C. Try It Out**

*   Click the **Try it out** button on the endpoint section.
    
*   Fill in the fields:
    
    *   For **file uploads**: Use the file picker to select your document.
        
    *   For other parameters (e.g., trace ID, prompt): Enter the required values.
        

**D. Execute**Click **Execute**. The UI will display:

*   The full request sent (method, URL, headers, and body)
    
*   The live response from your API (status code, headers, and JSON content)
    

You can repeat these steps for any endpoint!

5\. View Responses
------------------

All responses — status code, response body, and error messages — will be displayed directly below the request form in real-time. This helps you easily debug and refine your API usage.

*   **Success Example:**
    
    *   A JSON object with analysis/classification results.
        
*   **Error Example:**
    
    *   Error code and helpful message, such as missing required fields or invalid API key.