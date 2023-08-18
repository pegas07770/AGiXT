# Conversations

Injecting `{conversation_history}` into a prompt will allow the AI to use the last 5 interactions of the conversation as context for the next response.  This is useful for keeping a conversation going with the AI where it is aware of the history of your conversation.  If you want to keep talking to it about the same docs with out the history, start a new conversation and keep going with the same agent without any retraining of the documentation. Any conversations you have with the AI will be saved in the `agixt/conversations` directory and will also be viewable from inside of the AGiXT Streamlit Web UI.

Conversations are not limited to a single agent, you can switch between agents in a conversation to simulate a group conversation between yourself and multiple agents. This is useful for managing a team of agents.