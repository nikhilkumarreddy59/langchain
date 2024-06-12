
# Langchain Notes




* L1-Model_prompt_parser


    * Preparing instructions (prompts) for the LLM. It takes raw text and formats it in a way the LLM understands to get the desired output.
* L2-Memory

    * ConversationBufferMemory - remembers all the chats 
    * ConversationBufferWindowMemory - k argument
    * ConversationTokenBufferMemory - based on tokens it remebers
    * ConversationSummaryMemory  -  sumarriezes the past .. and then remembers 

* L3-Chains
    * Sequential Chains
        * SimpleSequentialChain - Single input and Single output ... ideal for single workflow 
        * SequentialChain - This offers more flexibility, allowing for multiple inputs and outputs at each step. This enables intricate workflows where you might combine LLM outputs with other data or perform additional processing before feeding it to the next step.
    * Router Chain
        
        - This chain adds decision-making capabilities. It takes an input, evaluates it based on pre-defined logic, and then routes it to the most suitable sub-chain for processing. This allows for branching workflows depending on the nature of the user input.


* L4-QnA over Documents 

    * Types of File Loaders
    * Stuff Method
    *  ![image](https://github.com/nikhilkumarreddy59/langchain/assets/96858425/a1219a32-129e-45de-a3de-c73baa271986)
    * 

* L5-Evaluation --IMP --Revisit

    * 


* L6-Agents

    * Tools - can intereat with API's, functions, other LLM"S also .. and langchain has multiple community tools ... 
    * Agents - Decision making and perform actions in sequence 

    * Together can make unlock the true potential of the langchain 



