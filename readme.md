#Alfred workflow baidu translate  (v2.0)
----------------------------------

##Function
Detect the input language automatically and translate to different languages by baidu translate.


##Principle
Get the users' inputs -> POST them to baidu translate api -> Grasp  response results -> Arsing the result to xml format which can be recognized by Alfred.

##Direction for use
‘bt’ （keyword） ＋ space ＋ words/sentences (in different languages)


##Annotation
When the input language is non-Chinese, the aimed translate language will be set to chinese automatically.  
When the input language is Chinese, the aimed translate language will be set to English automatically. 


##Test Cases
1. English to Chinese
![image](EN－CH.png)
2. Chinese to English
![image](CH－EN.png)
3. Japanese to Chinese
![image](JP－CH.png)
 
----------------------------------------- 
## V2.0 Updated on July 17th, 2014

1. Add notification when press "return".
2. Redirect to author's home page after pressing "return"
3. Copy website link of author's home page automatically.

Workflow:
![image](workflow_baidutranslate.png)
----------------------------------------- 
## Updated on January 16th, 2015

Now the workflow is available on <a href="http://www.alfredworkflow.com/">Alfred2 Workflows List</a>.

----------------------------------------- 
## Updated on April 14th, 2016

Migrate to most updated Baidu translate API.





