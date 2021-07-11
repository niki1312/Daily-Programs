class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        result=[]
        used={}
        for i,num in enumerate(nums):
            complement = target - num
            
            if complement not in used:
                used[num] = i
            else:
                result.append(i)
                result.append(used[complement])
        return result   
