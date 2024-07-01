# pt_to_safetensors_converter_notebook

TODO: implement full workflow IE running container from docker CLI, grabbing token, uploading .pt to work/ directory, etc. 
Same as main but local and inside a docker container running a base jupyter environment to prevent at least casual malicious code execution (https://github.com/DiffusionDalmation/pt_to_safetensors_converter_notebook) 

This notebook provides a simple tool to convert Stable Diffusion-related model files from .pt to safetensors format. Because of security concerns around .pt files and their ability to execute potentially malicious code, some people might prefer to share their Stable Diffusion-related model files in the more secure SafeTensors format instead.

No warranty expressed, implied, or really even considered. Use any code you find online at your own risk.
