# Deep_Learning_AI_Tutorials
Py notebooks for the tutorials with up to date code 
Link to the tutorial - https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/
Link to the Lang-x documentation - https://python.langchain.com/api_reference/index.html

Notebooks contain the code files to follow along with the tutorial.

Some of the lessons have 2 ways of solving a problem, for those I have separated out the ways into different notebooks so that they can be run/modified individually.

Updates done to the tutorial code:
  1. Code updated as per latest LangGraph API version (including for Tavily Search API integration)
  2. Code updated as per latest OpenAI API version
  3. Commented out LangGraph graph display as it is difficult to install LangGraph without installing multiple other dependencies
  4. Used environment variables to set API KEYS

Python v3.12
Setup the project in Jupyter:
1. Launch jupyter lab, create a new folder
2. In the terminal: cd <new folder name>
  python -m venv <give a name>

Setup environment variables on macOS:
1. Find out which shell your OS is using: echo $SHELL
   Below commands use zsh but replace zsh with the name of your shell in case it is different
2. Set the environment variables OPENAI_API_KEY, LANGCHAIN_API_KEY, TAVILY_API_KEY, USER_AGENT using this template : echo "export <keyname>='<keyvalue>'" >> ~/.zshrc
3. Reload the script : source ~/.zshrc
4. Echo $MY_VARIABLE to verify that variable is set

Install below python dependencies (recommended one by one so that errors can be monitored): 
pip install <lib name>

langgraph
langgraph-prebuilt
langgraph-sdk
langgraph-checkpoint-sqlite
langsmith
langchain-community
langchain-core
langchain-openai
notebook
tavily-python
wikipedia
trustcall

Reach out in case any of the installs are failing or if the code needs further updates.





  
