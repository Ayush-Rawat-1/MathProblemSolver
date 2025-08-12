🧮 Text-to-Math Problem Solver & Data Search Assistant
A Streamlit web-app that lets users type any natural-language math question (or anything that needs Wikipedia facts) and watch a ReAct-style agent powered by Google Gemma-2-9B solve it step-by-step.
Live reasoning is rendered in the UI thanks to the built-in StreamlitCallbackHandler.

🔧 What it does
| Feature                   | How                                                                             |
| ------------------------- | ------------------------------------------------------------------------------- |
| **Natural-language math** | Converts “I have 5 bananas …” into symbolic math and solves it.                 |
| **Wikipedia look-ups**    | Retrieves missing facts (e.g. “speed of light in km/s”).                        |
| **Explainable AI**        | Shows every **thought → tool call → observation** cycle in expandable UI cards. |
| **Persistent chat**       | Keeps a conversation history for the session.                                   |

