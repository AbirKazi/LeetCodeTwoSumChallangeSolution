# LeetCodeTwoSumChallangeSolution
This is the solution I came up with for the "Two Sum" Challange from LeetCode


var nums = [2, 7, 11, 15];
var target = 22;
myFunction(nums,target)

function myFunction(nums, target) {
  var foundIndexes = true;
    for(var i = 0; i < nums.length; i++){
      for(var j = 0; j < nums.length; j++){
        if(nums[i] + nums[j] == target){
          if(foundIndexes){
          console.log(nums[i] + " " + nums[j]);
            foundIndexes = false;
        }
        }
      }
      }
    }
