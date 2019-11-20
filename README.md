## Path to test your example:

If you built onnxruntime from source the path to onnx runtime server on linux is: ./onnxruntime/build/Linux/<Build_Config>/onnxruntime_server

Example:

```
ajinkya@ajinkya-H310M-S2:~/Documents/onnxruntime/build/Linux/RelWithDebInfo$ ./onnx_test_runner /home/ajinkya/Documents/onnxruntime/onnxruntime/test/testdata/transform/matmul_add_fusion/2Input/
result: 
	Models: 1
	Total test cases: 1
		Succeeded: 1
		Not implemented: 0
		Failed: 0
	Stats by Operator type:
		Not implemented(0): 
		Failed:
Failed Test Cases:
```
