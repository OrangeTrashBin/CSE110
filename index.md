# Who's Yiju Li?
![](UCSD.jpg)


1. [Who's Yiju Li](#answers)
2. [More Details](#more)
3. [Future Work](#future-work)

## Answers
This question has become a puzzle for human beings for a really long time. And here are some assumptions:
- He might be a **UCSD Student**
- He might major in **Computer Engineer**
- He might also major in **Applied Mathematics**
- He loves playing **guitar**
- He loves playing **[Apex Legends](https://www.ea.com/games/apex-legends?isLocalized=true)**


## More
### Yiju's frequently speaking sentence
    It doesn't matter
### His code
We found out one of his code on the internet:

~~~~
class Solution:
    def pathSum(self, root: Optional[TreeNode], targetSum: int) -> List[List[int]]:
        if root == None:
            return []
        if root.val == targetSum and root.left == None and root.right == None:
            return [[root.val]]

        left = self.pathSum(root.left,targetSum-root.val)
        right = self.pathSum(root.right,targetSum-root.val)
        r = left + right
        print(root.val)
        i = 0
        n = len(r)
        while(i<n):
            r[i] = [root.val]+r[i]
            i+=1
        return r
~~~~

## Future Work
- [ ] Found out his carrier plans
- [X] Getting his education experience

