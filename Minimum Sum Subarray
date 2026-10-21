
class Solution {
    public int minSubarraySum(int[] arr) {
        int currentSum = arr[0];
        int minSum = arr[0];

        for (int i = 1; i < arr.length; i++) {
            currentSum = Math.min(arr[i], currentSum + arr[i]);
            minSum = Math.min(minSum, currentSum);
        }

        return minSum;
    }
}
