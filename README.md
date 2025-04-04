# mabl Postman Collections
This repository contains Postman collections that you can view, edit, and [import into mabl as API tests](https://help.mabl.com/hc/en-us/articles/19078193969940).

> **Contributions welcome!**
> Your contributions help us build a more comprehensive resource for the mabl community.
  
## gen-ai
Send text or multimodal input to one of the following models and generate a response:
- [Anthropic Claude](https://docs.anthropic.com/en/api/getting-started)
- [Google Gemini](https://ai.google.dev/gemini-api/docs)
- [OpenAI GPT](https://platform.openai.com/docs/api-reference/introduction)

When [shared variables](https://help.mabl.com/hc/articles/17750199158804) is enabled, you can incorporate these tests into a [mabl plan](https://help.mabl.com/hc/articles/17780887930516) to:
- Validate text or images generated in an earlier test run
- Generate input for a subsequent test run

## mabl_public_api
A Postman collection of our public api found on [api.help.mabl.com](https://api.help.mabl.com/reference) with endpoints, path variables, query parameters and post-request response validation tests already included. 

To use this collection, you need access to a mabl workspace to create your own [API key](https://help.mabl.com/hc/en-us/articles/17776006239764). Learn more about authenticating requests to the mabl API [here](https://api.help.mabl.com/reference/authentication).

> Before you import this collection into mabl, [create an application](https://help.mabl.com/hc/en-us/articles/23120982365716) called "mabl API" and assign it a base URL of `https://api.mabl.com`. Then, when you import the collection, select "mabl API" as the application.

### Updating placeholders
After importing into mabl, replace the placeholder value with your actual API key in the [test-level auth settings](https://help.mabl.com/hc/en-us/articles/25298660330516).

Many endpoints have ID placeholders in the query or path params. See our article on [mabl resource IDs](https://help.mabl.com/hc/en-us/articles/17782745983636) for more details on how to get these IDs.

### Submitting data
POST and PATCH requests that submit data have commented-out pre-formatted raw JSON containing any key/value pairs accepted by the endpoint. Uncomment any lines or multi-line arrays needed for your request, and replace the placeholder value with the value you want to submit. Note that placeholder values indicate what data type should be used for that key.


