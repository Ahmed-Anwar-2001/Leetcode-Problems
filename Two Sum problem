class Solution:
    def twoSum(self, nums: list[int], target: int) -> list[int]:
        flag = False
        for i in range(len(nums)):
            if flag==False:
                for j in range(len(nums)):
                    if nums[i]+nums[j]==target and i!=j:
                        flag = True
                        return [i,j]
                        

obj1 = Solution()
obj1.twoSum([2,7,11,15],9)
