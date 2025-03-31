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
A postman collection of our public api found on our [reference page](https://api.help.mabl.com/reference) with end points, path variables, query parameters and post-request response validation tests already included. POST and PATCH requests that submit data have commented-out pre-formatted raw JSON containing any key/value pairs accepted by the endpoint. Uncomment any lines or multi line arrays needed for your request and replace the placeholder value assigned to the keys you need to submit. Note the placeholder value indicates what data type should be used for that key.



To use these collections, you’ll need to register for the service and create your own API key. After importing into mabl, replace the placeholder value for the API key variable with your actual API key. For the mabl public API collection, this value can be found under the Authentication tab for the mabl APIs parent folder.


