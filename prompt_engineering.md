# Prompt Engineering – ELI5 (Explain Like I’m 5)

Prompt engineering is all about crafting clear, specific instructions or questions that you feed to an AI system. Think of it like giving directions to a friend: if you say “Let’s meet at the store,” your friend might ask, “Which store?” or “What time?” Similarly, AI models need good prompts so they can produce helpful responses.

## Why Is Prompt Engineering Important?
- **Clarity:** A clear prompt gives the AI a precise direction. 
- **Context:** The more relevant information you give, the more accurate your answer.
- **Creativity:** You can tailor prompts for various tasks—brainstorming, summarizing, or even storytelling.

## Example of a Basic Prompt
If you’re planning a day out in San Francisco and you want AI to help, you might start with something simple:

Generate a list of hikes near SF.


This prompt is direct and should yield a handful of hiking options within the San Francisco area. But maybe you have specific requirements, such as the length of your hike. Here’s a more refined prompt:

Generate a list of hikes near SF that take 2 hours to complete.



By adding the detail about time (2 hours), the AI knows to filter out hikes that take significantly longer or shorter. This is what **prompt engineering** is all about—giving enough context so that the AI can zero in on the best possible response for your needs.

## The Anatomy of an “01 Prompt”
Greg Brockman (one of the co-founders of OpenAI) tweeted about “The Anatomy of an 01 Prompt,” illustrating how to craft instructions effectively. Here’s an **ELI5** version of what that means:

1. **“0” Stage: Provide the context**  
   In this stage, you give the AI all the background information it needs. For our hiking example, that might mean mentioning your location (San Francisco) and constraints (hikes must be around 2 hours).

2. **“1” Stage: Specify the outcome or task**  
   This is where you directly state what you want the AI to do: “Generate a list of hikes...” or “Summarize these text snippets…,” etc.

Combining both stages (the “0” and the “1”) gives you a prompt that is both **rich in context** and **clear on the objective**. For example:


I want a list of the best medium-length hikes within two hours of San Francisco. Goal Return Format Warnings Each hike should provide a cool and unique adventure, and be lesser known. For each hike, return the name of the hike as I'd find it on AllTrails, then provide the starting address of the hike, the ending address of the hike, distance, drive time, hike duration, and what makes it a cool and unique adventure Return the top 3. Be careful to make sure that the name of trail is correct, that it actually exists, and that the time is correct. For context: my girlfriend and i hike a ton! we've done pretty much all of the local SF hikes, whether that's presidio or golden gate park we definitely want to get out of town -- we did mount tam pretty recently, the whole thing from the beginning of the stairs to stinson - it was really long and we are definitely in the mood for something different this weekend! ocean views would still be nice. we love delicious food. one thing i loved about the mt tam hike is that it ends with a celebration (Arriving in town to breakfast!) The old missile silos and stuff near Discovery point is cool but I've just done that hike probably 20x at this point. We won't be seeing eachother for a few v weeks (she has to stay in LA for work) so the uniqueness here really counts.
