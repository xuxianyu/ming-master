---
sidebar: false
---

# ming 
## 联系方式 
* 邮箱 18120580001@163.com 

## 工作经历 
<my-timeline :eventList="workerHistoryEventList"></my-timeline>


## 技能

<my-word-cloud :words="myWords"></my-word-cloud>





<script >
export default {
      data(){
        return {
          workerHistoryEventList: [
          '2017-12-01~至今 昂立教育(java开发)',
          '2017-03-01~2017-11-25 牧美信息科技(java开发)',
          '2016-06-01~2017-02-28 电信外包(java开发)'
          ],
          myWords: [
                ['java',30],
                ['docker',20],
                ['linux',10],
                ['devops/sre',20]
          ]
        };
      }
    }
</script>
