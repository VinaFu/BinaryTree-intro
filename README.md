# BinaryTree-intro

https://www.youtube.com/watch?app=desktop&v=fAAZixBzIAI
  定义
    只有一个root
    不多过2个子集
    从root到Leaf只有一条路径

  呈现方式
    一条支路走到底，再换下一条。
    需要先判断下面还有没有子集。
    
    
    
   depth- first- values： Stack 竖向排序
      （stack.pop）
   breadth-first-valües： Queue  横向排列
      （queue.shift）
      
    用法：
      1）查items - tree includes
      2）查总和 - tree sum
      3）查最小值   - tree min value
      4）Max root to Leaf path summ
      
      
   1. 查target是否在binary里面
    1） 暴力
    2） 看它的子集是否有，否定这个。
    ｜｜ or 
      然后 false or false = false
      true or false = true
      
      
    2. total += current.val
      or
      sum root.left； sum root.right
      
      
    3. 用stack来一遍；queue来一遍；root.left+root.right来一遍
      
      
      
      
     4. 
     选子集最大， 然后和上面相加
     recursion
     maxChildPathSum = Math.max(maxPathSum(root.left), maxPathSum(root.right))
     root.val + maxChildPathSum
      
      
   
    
    

