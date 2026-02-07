# ConvoBuddy
# Day 1
An AI-powered conversational language tutor designed to help learners of all levels improve their day-to-day communication skills in a practical and engaging way. This intelligent system leverages advanced natural language processing (NLP) and machine learning algorithms to understand user input, respond naturally, and simulate realistic conversations across a wide range of everyday scenarios, from ordering food and shopping to socializing with friends or handling travel situations. The tutor not only provides instant feedback on grammar, vocabulary, pronunciation, and sentence structure but also adapts dynamically to the learner’s proficiency level, learning style, and progress over time. By tracking performance and remembering past interactions, it creates personalized learning paths and challenges, ensuring that practice sessions are both effective and motivating. Additionally, the platform encourages active participation through interactive dialogues, role-playing exercises, and scenario-based tasks, making the learning experience immersive and closely aligned with real-life communication needs. Its goal is to build confidence, fluency, and practical language skills in a way that is convenient, flexible, and accessible anytime and anywhere, empowering learners to use the language naturally in everyday life without fear or hesitation.

# Day 2
prototype 1 was made useing lovable AI. prototype 1 is a simple chat box that help you with learning English. the AI would respond your question but the user  must start the conversation.
https://chatty-coach.lovable.app

# Day 3
Project Description
This project is a voice-first conversational AI application where the AI automatically starts the conversation using spoken audio when the app opens. The user responds by speaking, and the AI replies using voice, creating a two-way voice interaction.

How It Works
1.	When the app starts, the AI plays a spoken greeting.
2.	The user responds using voice or text.
3.	User speech is converted to text using speech-to-text.
4.	The AI processes the input and generates a response.
5.	The response is converted to speech and played back to the user.

Current Status (Day 3)
•	Voice-based AI conversation implemented
•	AI initiates the conversation automatically
•	Basic speech-to-text and text-to-speech workflow working

# Day 4
•	Tested voice-first interaction with short spoken inputs
•	Identified latency caused by long AI responses
•	Noted robotic tone in voice output
•	Planned prompt iteration to improve naturalnes

Test Questions:
1.Hi
2.How are you?
3.I’m feeling bored
4.Can we practice English?
5.I didn’t understand that
6.Tell me something interesting
7.I’m tired today
8.What should we talk about?
9.Can you help me speak better?
10.Okay

# Day 5
Connected the AI model to the app interface in Lovable AI.
Designed user flow: AI starts the conversation, user responds by voice then AI replies.
Added basic UX: microphone indicator, reset conversation option, and safe logging of inputs/outputs.
Known issues: AI sometimes mishears words; mic timing can be slightly off.
Demo link: https://convobuddyaiapp.lovable.app

# Day 6
- Reviewed input handling and ensured safe processing of user speech and responses.
- Verified no API keys or secrets are exposed in the repository.
- Fixed key bugs, including microphone timing after AI speech.
- Identified known limitations with speech recognition in noisy environments.
- Added AI personality for more engaging conversations.
- Enabled user selection between male and female AI voices.
- Continued development using Thunkable AI due to limitations in the initial tool, while maintaining core functionality and security practices.

# Day 7
- Deployment target: Thunkable AI Live Preview
- Smoke tests: AI starts conversation, captures user speech, responds with voice; no crashes
- Performance: acceptable latency for demo
- Fallback: revert to last stable version if issues
- Decisions: focused on voice-only interaction; planned feature to have AI prompt users to use learned words in sentences (implementation limited by token availability)
- Blockers: app store publishing requires additional setup; further real-device testing needed

Planned feature: After teaching new words, the AI will prompt users to use them in spoken sentences to reinforce learning. Implementation may be limited by AI token availability in Thunkable.
