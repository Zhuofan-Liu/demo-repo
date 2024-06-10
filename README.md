# APISWEA 2024 International Annual Conference Training (6.3, Chengdu, China)
## Term Intro

**knowledge cut-off** 
- e.g. chatgpt 2021

**training data**
- trained by web data, not the academic literature
- gpt don't know chinese very well

**searching vs. prompting**
- searching in the internet  vs. set of instructions

**word prediction**
- principle of predicting words e.g. once upon a (time)

**hallucinations(depend on the task)**
- it's not give you wrong information, it;s just give you the predicction. you have yo clarify. people think gpt have all of the information, but the truth is not, it just learn the model, but not the research(misuse of the literature review); you could give them some literature and let them to surrarize is  possible.
- coz cut-off and prediction

**model size/parameters**
- the larger the model, better performance; the size is examined in the parameters(one trillion)
- small models can run in personal computer

**tokens**
- smaller of words (inter)-(face)

**API vs web interface**
- web: just copy and paste single thing
- API: (APPLICATION PROGRAMMING INTERFACE) collect thousands of data through your computer and other sources; climate (phone and other sources)
use a model, ask them if is have API, how tokens to sent and receive
e.g. CNKI, thousands of research, write code to collect these 

**language model vs code model**
- code model along with its language model(optimaze code model, give you better results)

**context window**
- (measure in the number of tokens; larger context needs better memory)
- needle in the haystack
    lost in the middle: seperate them
    
**in-context learning**
- could teach them to learn with provding new info

**Guardrails, censoring(what are some limitations)**
e.g. sensitive topics

## models
**speciality models**
    multimodel
    mixture of experts (MOE)

**LLM agents/tools**
    web searching
    API
    calculator/python

## model types
- closed(just use)
- open source(download on your own computer, no sending to the cloud)
- open source-gate
- open weight(do additional thing)

don't send personal info, coz it will go to the cloud

data 
format
Natural language processing/tasks
converting unstructured data to structured data; extracting things ;summaring; translating; 

**markdown**
format; 

**Json**
type of data structure; format

**word embeddings**
pdf--raw text; must perserve the data

**raw text/plain test**
txt file


#deepseek ( another model; like gpt): traind in bilingual, free; 

prompt
system prompt: collect with the sysytm
user prompt: give task to the system


## models

各有优劣，基础工作
local model无需联网，保护隐私

**Llama3**
- open source

- 电脑终端：search terminal,但是需要先下载软件， off-line; 本地部署（Llama3可以终端， 也可以网页，相当于嵌入电脑里面，无需联网；小空间即可

**Mistral**
- french; cheap; good perform model; download
;codestral :code-based model(python)

**Deepseek**
- language and code model（API使用，无需vpn）编码

**Phi**
- not perfect; run in own computer, small model

**Qwen**
- 通义；免费，python

**Yi**
- trained in bilingual; translation is good.

**文心一言**
- 百度

**Kimi( has its prompt templet)**
- 办公行政

**cloud**
- 文科类语言理解

**chatgpt**
- 英文

## promptingStategies
prompt engineering; 
Be careful: different prompting stategy will have different outcomes.

think it as a human
设置让其效果最优
break it down, and revise it 

**e.g. C.R.E.A.T.E framework (a strategy)**
     
    1.context(set the specified context)
    e.g. you are an expert in a certain area, social worker, data analyst
    
    2.result(What is the delivery )
     e.g. you are help me to edit the journey; code -- put in Json format; 
     
    3.explanation
    e.g. I want 250 words; I want XX,please treat me like a 50 year old.
    
    4.audience
     e.g. this is for technical audience(editor); people without technical audience
     
    5.tone
    e.g. make this conversational, not direct; make it serious, humorious
    
    6.edit(over and over again)
    e.g. expand, 

可以给对话命名， name the dialogue, and it will be more precise

both python and web-based interface need prompting strategies. but python could be used to deal with large text.


#zeroshapedprompting
no exampls

#aimedshapedprompting: teach the model as what you what, give the examples of the outcome you want. The 
clear context or open a new chat

### Examples
1.The 

2.###examples
-xxx(shift+enter)
-xxx
-xxx

3.###here is the abtract you need to 

4.###Requirement(emotional prompt)


#fromUnstructedToStracturedInfo
1.the text you want, then your prompting words
e.g., the prompting words could be like this: determine whether the summary indicates a problem of drugs or alcohol. if so, return the names of the people and the substances.

visual studio code
pandas模型调用地较多


## API
terminal
retreival 













