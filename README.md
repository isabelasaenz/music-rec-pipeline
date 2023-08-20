## Music Recommendation ETL Pipeline
### How it works

1. **Extraction:** JSON data containing user preferences is extracted and loaded into the pipeline.

2. **Transformation:** User preferences are transformed into prompts for music recommendations using GPT-3.

3. **Recommendation Generation:** The transformed prompts are sent to the GPT-3 API to generate personalized music recommendations.

4. **Loading:** The generated recommendations are printed for each user.

(Ensure you have a valid OpenAI API key assigned to `openai.api_key`)
