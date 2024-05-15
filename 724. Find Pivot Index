/**
 * @param {number[]} nums
 * @return {number}
 */
var pivotIndex = function(nums) {
    let leftsum=0, sum=0;
    nums.forEach(x =>{
        sum+=x;
    });
    for(let i =0; i <nums.length ; i++){
        if(leftsum == sum - leftsum - nums[i]){
            return i;
        }
        leftsum+= nums[i];
    }
    return -1;
};