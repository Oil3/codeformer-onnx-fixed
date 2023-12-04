codeformer fixed

dec042023: It's a mixed precision model that keep fp32 for inputs/ouputs, basically allows to just swap with the other model. Let's name it codeformer "fixed" because it notably removes the square bug.
It seems to come from some gpt app.


# codeformer-fixed
onnx codeformer i found in my files that is half the size, faster and fixed the square bug I have with the original.

to use: rename/swap with the original model.

Download from huggingspace [https://huggingface.co/Oil3/faster_codeformer_onnx](https://huggingface.co/Oil3/faster_codeformer_onnx)

Direct download from github: [https://github.com/Oil3/codeformer-onnx-fixed/releases/download/codeformer_onnx/CodeFormer_fixed.onnx](https://github.com/Oil3/codeformer-onnx-fixed/releases/download/codeformer_onnx/CodeFormer_fixed.onnx)


"original" codeformer onnx sha256 9aa48fc4b21224d85784c9a58885201284ec8e590b988126db2c07495b421d36 filesize 376,821,951 bytes (376.8 MB on disk)

"fixed" codeformer onnx sha256 9c3ae2ce2de616815815628f966cdef5d9466722434a1be00c0785ec92e2a94f filesize 188,577,164 bytes (188.6 MB on disk)

