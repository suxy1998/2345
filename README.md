
 鉴于上述情况，研究者认为，此次网络试调查问卷的有效问卷标准如下：  
 （1）问卷回答时长在10~60分钟之间（包含端点值）；  
 （2）排除医务人员被试；  
 （3）排除学生被试。  
   
## 请根据上述要求，完成以下问题：
**（1）**
计算有效问卷率；

__（2）__
选择合适的指标，说明效问卷的回答时长及其分布。

__（3）__
新生成两个变量，一为*province*（省份），一为*city*（省会城市或地级市，），此部分信息均在*ip*一列中可以找到。统计各省份、各城市有多少被试参与调查。

+ 注：当然，*ip*显示云南丽江，不一定被试为丽江市区（城市户口），也可能是丽江农村（农村户口）。所以这里的城市，只宜理解为行政管辖上的归属地所属，而不能体现城乡差别。

+ 提示：建议使用Hadley的stringr及lubridate这两个包进行字段处理和时间处理的相关操作。
     
        
 # 四、统计操作（20分）
   
|**校外(out)** | 2.0|2.3|1.1|-2.0|-1.9|5.6|2.6|1.1|5.6|8.2 | 
| :-: | :-: | :-: | :-: |:-: |:-: |:-: |:-: |:-: |:-: |:-: |
| **校外(out)** | **1.6**|**3.1**|**-2.8**|**0.0**|**0.2**|**2.9**|**-0.9**|**3.8**|**0.7**|**-0.1**|
  
   正数表示体重增加，负数表示体重减少。完成以下任务，写出命令和并附上结果。  
   （1）将此数据输入R，命名为testscore。  
   （2）估计校内住宿新生和校外住宿新生的平均体重增减量之差(校内－校外)的98%双侧置信区间，假定所有条件满足。基于这一区间，研究者有无足够信心认为校内住宿新生与校外住宿新生的平均体重增减量有无区别？  
   （3）若研究者想判定，平均而言校内住宿新生比校外住宿新生更容易“长胖”，应当使用什么样的置信区间？如果用R实现？  
   （4）若使用显著性检验法判定校内住宿新生比校外住宿新生更容易“长胖”，应当使用什么方法和R命令实现？ 
 # 五、综合应用（10分） 
   
   
     
    
   
   
 # 六、开放性问题（10分，不少于500字）
此题请用电脑打字，最后请说明电脑统计的字数（不计空格）。

结合自身的专业背景，谈一谈你对大数据技术对本专业研究的应用前景，以及R在其中可扮演的角色。并由此谈一谈你对本专业数据处理类课程设置、教学内容、教学方式的建议。
