/*Given an integer array nums and an integer val, remove all occurrences of val in nums in-place. The order of the elements may be changed. Then return the number of elements in nums which are not equal to val.

Consider the number of elements in nums which are not equal to val be k, to get accepted, you need to do the following things:

Change the array nums such that the first k elements of nums contain the elements which are not equal to val. The remaining elements of nums are not important as well as the size of nums.*/


function removeElement(nums, val) {
    let k = 0; 

    for (let i = 0; i < nums.length; i++) {
        if (nums[i] !== val) {
            nums[k] = nums[i];
            k++;
        }
    }

    return k; 
}


const nums1 = [3, 2, 2, 3];
const val1 = 3;
const k1 = removeElement(nums1, val1);
console.log(k1); 
console.log(nums1.slice(0, k1)); 

const nums2 = [0, 1, 2, 2, 3, 0, 4, 2];
const val2 = 2;
const k2 = removeElement(nums2, val2);
console.log(k2); 
console.log(nums2.slice(0, k2));
