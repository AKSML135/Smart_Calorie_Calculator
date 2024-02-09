## Descritpion - 
- This is Multimodal RAG that takes image of food as an input and a prompt (what you want to know about this image) and provides you the answer along with calories of food.

## Tech Used - 
- Streamlit (for entire UI)
- Google Gemini pro vision model (to read image and generate output)
## Gemini Pro Vision	Model  = {last updated	December 2023}
- Model code ->	models/gemini-pro-vision
# Model capabilities	
- Input: text and images
- Output: text
- Can take multimodal inputs, text and image.
- Can handle zero, one, and few-shot tasks.
- Supported generation methods	generateContent
- Input token limit	-> 12288
- Output token limit ->	4096
- Rate limit	-> 60 requests per minute

## Steps -
- Click on upload button to upload the picture and write your prompt in text box provided
- click on submit button to get the response

## Screenshot of UI - 
