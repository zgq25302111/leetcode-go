package main

import "fmt"

func twoSum(nums [3]int, target int) []int {
	m := make(map[int]int)
	for k, v := range nums {
		if idx, ok := m[target-v]; ok {
			return []int{idx, k}
		}
		m[v] = k
	}
	return nil
}

func main() {
	myArray := [3]int{2,3,7}
	fmt.Println(twoSum(myArray, 10))
}
