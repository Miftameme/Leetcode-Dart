class Solution {
  List<int> twoSum(List<int> numbers, int target) {
    int n = numbers.length;
    for (var i = 0; i < n - 1; i++) {
      for (var j = i + 1; j < n; j++) {
        if (numbers[i] + numbers[j] == target) {
          return [i, j];
        }
      }
    }

    return [];
  }
}
