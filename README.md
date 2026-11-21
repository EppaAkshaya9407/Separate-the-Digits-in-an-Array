# Separate-the-Digits-in-an-Array
class Solution:
    def separateDigits(self, nums: list[int]) -> list[int]:
        if nums is None:
            return None
        r=[]
        for i in nums:
            for j in str(i):
                r.append(int(j))
        return r
